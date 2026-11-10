# SafeWalk — Campus Safety Prototype

React + Express + MongoDB scaffold for opt-in device location, a safety check-in timer, an emergency contact directory, a press-and-hold SOS action panel, and non-emergency reports.

Run `npm install`, optionally copy `.env.example` to `.env` and configure MongoDB, then run `npm run dev`. Build with `npm run build` and run with `npm start`.

**Prototype limitation:** SOS does not notify responders, location is not streamed to contacts, and the sample directory has no phone numbers. Location access starts only after you tap the sharing control, and a map link is shared only after you request it. Verify and configure campus contacts and local emergency numbers, implement authenticated consent-based live sharing and incident handling, and conduct a safety review before real-world use. This prototype is not an emergency service.
