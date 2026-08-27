# Contributing to Ember Scripts

Thanks for contributing to Ember Scripts. This guide covers how to submit your scripts, formatting requirements, and community standards.

## Code of Conduct

Be respectful. Don't submit malicious scripts that:

- Steal accounts or cookies
- Contain malware or backdoors
- Target other players for harassment
- Attempt to break Roblox's anti-cheat in ways that harm the platform
- Include obfuscated or unreadable code

Scripts that violate these rules will be rejected.

## Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:

```bash
git clone https://github.com/your-username/ember-scripts.git
cd ember-scripts
```

3. Create a branch for your script:

```bash
git checkout -b add-my-script
```

Adding a Script

Choose the correct category folder:

```
scripts/
├── universal/        # Works in most games
├── combat/           # Combat-related
├── utility/          # Quality of life
└── game-specific/    # For specific games
    ├── blox-fruits/
    ├── pet-simulator/
    └── arsenal/
```

For game-specific scripts, create a subfolder with the game name if it doesn't exist.

Script Format

Every script must have a header comment:

```lua
-- Script Name: Infinite Jump
-- Description: Makes your character jump infinitely high
-- Author: YourName
-- Version: 1.0
-- Game: Universal
-- Date: 2026-01-15

-- Your script code here
```

Code Requirements

· No obfuscation — code must be readable
· Comments — explain complex sections
· No external loaders — unless from trusted sources (Infinite Yield is allowed)
· No key systems — scripts must be free to use
· Test your script — broken scripts will be rejected

Pull Request Process

1. Add your script to the correct folder
2. Update the README.md script list if adding a new script
3. Commit with a descriptive message:

```bash
git add scripts/universal/my-script.lua
git commit -m "Add my-script.lua — description of script"
git push origin add-my-script
```

4. Open a pull request on GitHub
5. Wait for review — respond to any feedback

Review Process

Maintainers will check:

□ Script works as described
□ No malicious code
□ Proper header comment
□ Correct category folder
□ No obfuscation
□ README updated if needed

License

By submitting a script, you agree to license it under GPL v3.0. This means others can use, modify, and distribute your script as long as they also use GPL v3.0 and include attribution.

Questions

Open an issue on GitHub or join the Discord.

Thank You

Every contribution helps build the Ember community. Your scripts make RoEmber better for everyone.
