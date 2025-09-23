# Beta Regression Checklist

## Quick checklist for a new iOS beta
- Review kernel changelog / XNU commits (if available)
- Test previously fixed crash primitives
- Run targeted fuzzers on new subsystems
- Monitor system daemon log differences (launchd, trustd, etc.)
- Verify sandbox policy changes
