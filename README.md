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


<img src ='Sample Output 1.png'>

