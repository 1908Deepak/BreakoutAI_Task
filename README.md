# Option Chain Data Fetching with Upstox API
This project retrieves and processes option chain data from the Upstox API. It is designed to fetch the highest bid price for put options (PE) and the highest ask price for call options (CE) for each strike price of an instrument like NIFTY or BANKNIFTY on a specified expiry date. Additional calculations include margin requirements and premium earned per option, and the results can be saved to a CSV file.

## Requirements
Python 3.7 or above

Vscode or Google Colab

CSV File

Upstox API

## Installation

```bash
   pip install virtualenv
```

Create virtualenv
```bash
    python -m virtualenv XYZ(FolderName)
```
Install Dependencies
```bash
    !pip install upstox-python-sdk
```
Clone Repository
```bash
    git clone https://github.com/1908Deepak/option_chain
```

## API Reference

#### Upstox API

```
  https://upstox.com/developer/api-documentation/open-api/

```
#### Authentication Access

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `secret_key` | `string` | **Required**. Your secret key |

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `redirect_url` | `URL` | **Required**. Your redirect Url |

#### Authorization Code

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Code`      | `string` | **Required**. code from redirect_url |

#### Access Token

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `access_token`      | `string` | **Required**. Token generated from url |


## Tech Stack

Language: Python

Software: Google Colab

## Introduction

[Brief Introduction of Project](https://www.loom.com/share/6489d5ea0dac49d4a32654fcb6082254?sid=a33ff71a-19ed-451e-bcdc-0e86d3a6e6fa)

## Support

For support, email deepaksingh190810@gmail.com

## License

[MIT](https://choosealicense.com/licenses/mit/)


## Documentation

[Documentation](https://docs.google.com/document/d/1hGIx8ahHNLQebnLw37qsk8uCbEO2oqHK/edit?usp=sharing&ouid=110553890098207369686&rtpof=true&sd=true)
