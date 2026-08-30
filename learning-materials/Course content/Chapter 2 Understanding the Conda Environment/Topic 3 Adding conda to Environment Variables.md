# Adding conda to Environment Variables

When you install Anaconda or Miniconda, the `conda` command-line tool is available in the terminal or shell where you ran the installation script. However, it may not work in other terminals or shells unless you add it to your environment variables. To add `conda` to your environment (so it works in any terminal or shell), follow these steps based on your operating system.

## Automatic Method (Recommended)

You can run this command in Anaconda Prompt to initialize `conda` for Command Prompt (cmd) or PowerShell:

```bash
conda init
```

- This modifies your shell's configuration to recognize `conda`.
- Restart your terminal after running the command.
- The process is automatic and you should be able to use conda from any directory in the terminal.

## Manually (If Needed)

Add these paths to the System Environment Variables:

1. **Open Environment Variables**
   - Press `Win + R` → Type `sysdm.cpl` to open System Properties → Click **Environment Variables**.

2. **Edit the Path Variable**
   - Find and edit the `Path` variable in System Variables.

3. **Add These Entries**