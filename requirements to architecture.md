# Mobile technology decision factors
Which of those factors are of which priority?
This prioritisation will allow us to select between React Native / Fultter / Embedded WebView / Hybrid (native + react native or native + flutter)

- User experience
  - Native scrolling experience (scrolling speed). Importance: ?
  - Internationalisation. Importance: ?
  - Authentication (Password, Face ID, PIN, Fingerprint, (Samsub token)). Importance: ? Which types are supported: ?
  - Theming. Importance: ?
- Supportability
  - Logging, gathering logs for SL3. Importance: ?
  - Action tracking (user actions). Importance: ?
- Speed of delivery
  - Autotests from day 1. Importance: ?
    - unit
    - e2e
    - component
    - cross-platform testing support
  - Developer experience
    - Time to start writing clean production-ready code. Expected time for the platform: ?
    - Debugging support. How smooth is it for the platform: ?
    - Server interaction: REST or Web Sockets? GraphQL? Open question
    - Components library. Can we do this for the platform?
    - Style library. Can we build it for the platform?
    - Sharing code with web. Importance? Can we do this for the platform?
    - Styleguide: unified and strict + linting. We need to agree that we need it
    - Simple technology landscape. Do we need more than 1 language to implement the feature with the platform?
  - Back-end for front-end approach. How far we go here?
  - Keeping language packs on back-end. Open question
- NFRs
  - Performance
    - Startup
      - Data caching (for faster startup). Is it supported: ?
    - No lags on chaning UI screens. Will it be possible for platform ?
  - App size. Expected numbers for the platform: ?
  - Memory consumption. Expected numbers for the platform: ?
  - Battery impactExpected numbers for the platform: ?
  - Security (restrict app code access to end-user): Will it be possible for platform ?

# Web technology decision factors

- User experience
  - List of browsers to support. Open question, Importance ?
  - Mobile web support. Open question, Importance ?
  - Internationalisation. Open question, Importance ?
  - Authentication. Open quest: password only? other approach on mobile web?
- Speed of development
  - Autotests from day 1. Importance: ?
    - Unit
    - E2E
    - Screenshots with tolerance
  - Developer experience. Open question
    - Dependabot? Can we have it?
    - React Saga or plain Middleware or React Thunk?
    - Styleguide + linting. We need to agree that we need it
- NFR
  - Start-up performance
    - SSR support. Do we need it?
- Supportability
  - Action tracking. Do we need it?
