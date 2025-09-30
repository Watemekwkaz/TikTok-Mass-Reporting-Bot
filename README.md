# TikTok Reporting Tool

Provides a tool to automatically report TikTok accounts and videos using browser cookies.

## Features

- **Account Reporting**: Report TikTok accounts for various reasons.
- **Video Reporting**: Scan and report videos from a specific TikTok account.
- **Multi-Threading Support**: Perform multiple reporting operations simultaneously.
- **Customizable Reasons**: Use predefined or random reporting reasons.

## Installation

- Clone the repository.

- Install the required dependencies:
  ```bash
  pip install -r requirements.txt
  ```

## Usage

### Main Script

Run the main script to start reporting:

```bash
python main.py
```

#### Required Inputs

- `username`: The username of the TikTok account you want to report.
- `sessionid`: TikTok session ID cookie if not auto-detected.

The script will perform the following:

1. Retrieve account and video information.
2. Report the account for all reasons.
3. Scan and report all videos from the account.

<!-- ### API Module

The `api.py` module provides a wrapper to interact with TikTok's API. Using this module, you can:

- Retrieve user information.
- Fetch videos from an account.
- Programmatically report accounts and videos.

  **Note:** The `jsvmp.hex` file is used for signing requests. -->

## Disclaimer

This tool is intended for **educational and ethical use only**. It is strictly prohibited to use this tool to harm, harass, or misuse in violation of TikTok or any platform's terms of service. The authors are not responsible for any misuse of this tool.

## Contribution

Contributions are welcome! Fork the repository and submit a pull request for improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
