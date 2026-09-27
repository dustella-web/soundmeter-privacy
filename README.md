# SoundMeter privacy site

Static, dependency-free privacy policy for Google Play. Deploy this directory to any HTTPS host that returns the page without login or JavaScript.

Required post-deploy steps:

1. Register the public URL in Play Console.
2. Set `privacy.policyUrl=<public-url>` in the release Gradle properties.
3. Verify HTTP 200 from a signed-out browser and a non-browser client.
