# Strategic Technologies Funding Leverage Elements

Show how European, national and private finance combine behind critical technology investments.

## Live demo

Run the frontend and backend locally with the installation steps below, then open `http://localhost:5173`.

## Screenshots

![Strategic technology funding dashboard](docs/screenshot.png)

## Main features

- Search and sort funding cases by technology, programme, owner or status.
- Create financing packages and advance real backend records.
- Summarise live case volume, approved packages and financing gaps.
- Expose reusable status-card and funding-desk web components.

## Technology used

Lit, TypeScript, Web Components, reactive controllers, Vite, Vitest, Spring Boot, Jakarta Validation, JUnit and Maven.

## Installation instructions

Use Node.js 20+, Java 21 and Maven 3.9+. Run `npm install`, then start the API with `cd backend && mvn spring-boot:run`. In another terminal run `npm run dev`.

## Commercial licensing/contact

Commercial licensing and implementation enquiries: `100402995+Amitesh2022@users.noreply.github.com`.

## Business problem and users

Programme managers, investment advisers and technology firms need to see how public contributions, national finance and private leverage form one delivery package.

## Key workflows

Find a technology package, create a funding case, review its accountable owner, advance the decision and verify the updated server state.

## Lit and Web Components highlights

Shadow DOM, reactive properties, keyed repeat directives, custom elements and a reactive pulse controller demonstrate portable browser-native components.

## Java backend highlights

Spring Boot exposes validated list, search, create and update endpoints, structured errors, a health endpoint, service/domain separation and JUnit tests.

## Architecture and state flow

The funding desk calls `/api/items`; Java validates and updates records; Lit renders the returned authoritative state inside reusable components.

## Accessibility and responsive behaviour

Labelled search, clear status text, strong contrast, keyboard controls and responsive component layouts support varied devices and input methods.

## Verification commands

Run `npm test`, `npm run lint`, `npm run build`, `cd backend && mvn test` and `mvn package`.

## Structure

`src/` contains the Lit elements, `backend/` contains the Java service, and `docs/` contains reviewed product media.

## Tradeoffs

In-memory storage keeps the example self-contained; production use would add durable ledgers, granular access, currency handling and programme integrations.

## Roadmap

Add leverage ratios, milestone finance, programme eligibility checks, portfolio exports and institution-specific views.
