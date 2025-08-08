# Fobiz MDM Bypass

A customized script to bypass MDM setup on macOS, based on assafdori/bypass-mdm. Works up to macOS Sequoia 15.5.

## Usage
1. Boot your Mac into Recovery Mode:
   - For Apple Silicon: Hold the power button until the startup options appear.
   - For Intel: Hold `Cmd + R` during boot.
2. Connect to WiFi and open Safari.
3. Navigate to this repository: `https://github.com/pasun-dev/fobiz-mdm-bypass`.
4. Run the script:
   ```bash
   curl https://raw.githubusercontent.com/pasun-dev/fobiz-mdm-bypass/main/bypass-mdm.sh -o bypass-mdm.sh && chmod +x ./bypass-mdm.sh && ./bypass-mdm.sh
   ```
5. Follow the on-screen instructions.

## Disclaimer
Use this script at your own risk and only on devices you own or have permission to modify. Bypassing MDM may violate organizational policies or local laws.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
