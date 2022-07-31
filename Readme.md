# Trading Desk (React) - Final Coding Assessment

## Overview

The purpose of this assessment is to assess your **skills and approach to composing a web app** given an API feed.

#### You'll be graded based on :

- Code Quality
- Completeness
- Logic
- Documentation of your project
- Similarity to

## Replicate the Trading UI given below

### Trading UI

<img width="1509" alt="Screenshot 2022-07-31 at 10 51 45 AM" src="https://user-images.githubusercontent.com/52570524/182011436-ac579315-578f-4740-adeb-66876a0aefdf.png">

## What to do?

Your goal is to replicate the trading page of Brine. Only use plain CSS or SCSS for styling.

We will be looking for a **well-designed**, well-commented, **responsive** and tested code in the submission.

Please include a `README` with setup instructions and any other documentation you created as part of your solution (Additional Marks)

Also, add very short info for the following to your `README`:

- Describe all the application functionalities
- Are there any improvements you could make to your submission?
- What would you do differently if you were allocated more time?

Once you complete implementation, please add the link to the hosted repository (e.g. Github). Alternatively, you may submit your code as a ZIP file too.

(NOTE: You have to use the latest version of v18 and react-router-dom v6)

## How should the application work?

The user of this react application should be able to view all the feature of Brine trading app. Only add dynamic nature to features set below.

1. #### Orderbook should be dynamic.
<img width="284" alt="Screenshot 2022-07-31 at 10 30 55 AM copy" src="https://user-images.githubusercontent.com/52570524/182011364-f9817b70-73b2-4f05-89d1-6e3560b06a75.png">

Where can we fetch the data?
`wss://api-betatestnet.brine.finance/liveorderbookwire`

Example Response:

    {
        "ethusdt": {
            "asks": [
                [
                    "1695.71",
                    "2.0"
                ],
                [
                    "1695.72",
                    "2.0"
                ],
                [
                    "1695.73",
                    "2.0"
                ],
                [
                    "1695.74",
                    "2.0"
                ],
                [
                    "1695.75",
                    "0.15"
                ],
                [
                    "1695.85",
                    "0.02"
                ],
                [
                    "1695.86",
                    "2.0"
                ],
                [
                    "1695.91",
                    "2.0"
                ],
                [
                    "1695.92",
                    "0.825"
                ],
                [
                    "1695.93",
                    "1.203"
                ],
                [
                    "1900.0",
                    "0.0558"
                ],
                [
                    "1925.98",
                    "0.025"
                ],
                [
                    "2000.0",
                    "0.1203"
                ],
                [
                    "2100.0",
                    "0.27"
                ],
                [
                    "2500.0",
                    "0.05"
                ],
                [
                    "3000.0",
                    "0.06"
                ],
                [
                    "4000.0",
                    "0.0017"
                ],
                [
                    "5000.0",
                    "0.001"
                ],
                [
                    "9523.0",
                    "0.0353"
                ],
                [
                    "9999.0",
                    "0.025"
                ],
                [
                    "50000.0",
                    "0.0425"
                ],
                [
                    "100000.0",
                    "0.0276"
                ]
            ],
            "bids": [
                [
                    "1695.45",
                    "0.176"
                ],
                [
                    "1695.44",
                    "0.007"
                ],
                [
                    "1695.41",
                    "0.221"
                ],
                [
                    "1695.38",
                    "0.032"
                ],
                [
                    "1695.37",
                    "0.612"
                ],
                [
                    "1695.36",
                    "2.0"
                ],
                [
                    "1695.33",
                    "0.023"
                ],
                [
                    "1695.3",
                    "0.058"
                ],
                [
                    "1695.27",
                    "0.02"
                ],
                [
                    "1695.26",
                    "0.012"
                ],
                [
                    "1695.25",
                    "0.15"
                ],
                [
                    "1695.22",
                    "2.0"
                ],
                [
                    "1695.21",
                    "2.223"
                ],
                [
                    "1695.12",
                    "1.86"
                ],
                [
                    "1695.11",
                    "2.0"
                ],
                [
                    "1695.06",
                    "2.0"
                ],
                [
                    "1695.05",
                    "2.0"
                ],
                [
                    "1694.99",
                    "1.0"
                ]
            ]
        },
        "btcusdt": {
            "asks": [
                [
                    "23757.26",
                    "0.001"
                ],
                [
                    "23757.27",
                    "0.0183"
                ],
                [
                    "23757.44",
                    "0.02"
                ],
                [
                    "23757.52",
                    "0.002"
                ],
                [
                    "23757.64",
                    "0.0028"
                ],
                [
                    "23757.67",
                    "0.001"
                ],
                [
                    "23757.81",
                    "0.078"
                ],
                [
                    "23758.07",
                    "0.0136"
                ],
                [
                    "23758.53",
                    "0.046"
                ],
                [
                    "23758.59",
                    "0.01"
                ]
            ],
            "bids": [
                [
                    "23753.31",
                    "0.0236"
                ],
                [
                    "23753.3",
                    "0.0147"
                ],
                [
                    "23753.13",
                    "0.0021"
                ],
                [
                    "23753.11",
                    "0.002"
                ],
                [
                    "23753.08",
                    "0.002"
                ],
                [
                    "23752.58",
                    "0.0018"
                ],
                [
                    "23752.57",
                    "0.001"
                ],
                [
                    "23752.48",
                    "0.0125"
                ],
                [
                    "23752.3",
                    "0.0041"
                ],
                [
                    "23752.24",
                    "0.01"
                ],
                [
                    "2600.0",
                    "6.2604"
                ],
                [
                    "545.0",
                    "0.0001"
                ],
                [
                    "500.0",
                    "0.02"
                ],
                [
                    "200.0",
                    "0.0185"
                ],
                [
                    "198.0",
                    "0.0285"
                ],
                [
                    "190.0",
                    "0.0044"
                ],
                [
                    "150.0",
                    "0.0597"
                ],
                [
                    "100.0",
                    "0.0044"
                ],
                [
                    "44.0",
                    "0.0019"
                ],
                [
                    "40.0",
                    "0.0254"
                ],
                [
                    "30.0",
                    "0.001"
                ],
                [
                    "23.0",
                    "0.001"
                ],
                [
                    "21.0",
                    "0.0006"
                ],
                [
                    "20.0",
                    "0.108"
                ],
                [
                    "14.0",
                    "0.0006"
                ],
                [
                    "10.0",
                    "2.0411"
                ]
            ]
        },
        "usdcusdt": {
            "asks": [
                [
                    "1.0",
                    "8906.77"
                ]
            ],
            "bids": []
        },
        "ethusdc": {
            "asks": [
                [
                    "1765.02",
                    "0.528"
                ],
                [
                    "1765.28",
                    "0.281"
                ],
                [
                    "1765.59",
                    "2.0"
                ],
                [
                    "1765.62",
                    "0.099"
                ],
                [
                    "1765.75",
                    "0.161"
                ],
                [
                    "1765.8",
                    "0.107"
                ],
                [
                    "1765.86",
                    "0.117"
                ],
                [
                    "1765.91",
                    "0.131"
                ],
                [
                    "1766.0",
                    "1.008"
                ],
                [
                    "1766.02",
                    "0.811"
                ],
                [
                    "1800.0",
                    "0.0026"
                ],
                [
                    "2000.0",
                    "0.001"
                ],
                [
                    "2500.0",
                    "0.005"
                ],
                [
                    "6000.0",
                    "0.008"
                ],
                [
                    "10000.0",
                    "0.0318"
                ]
            ],
            "bids": [
                [
                    "1764.2",
                    "0.001"
                ],
                [
                    "1763.72",
                    "0.001"
                ]
            ]
        },
        "btcusdc": {
            "asks": [
                [
                    "23935.32",
                    "1.5223"
                ],
                [
                    "24145.02",
                    "0.2071"
                ],
                [
                    "24145.27",
                    "0.0083"
                ],
                [
                    "24145.62",
                    "0.0125"
                ],
                [
                    "24146.12",
                    "0.0043"
                ],
                [
                    "24146.33",
                    "0.0622"
                ],
                [
                    "24146.99",
                    "0.4148"
                ],
                [
                    "24147.16",
                    "0.001"
                ],
                [
                    "24147.28",
                    "0.0306"
                ],
                [
                    "24148.37",
                    "0.001"
                ],
                [
                    "24149.99",
                    "0.285"
                ],
                [
                    "24300.0",
                    "0.0009"
                ],
                [
                    "24500.0",
                    "0.055"
                ],
                [
                    "24825.0",
                    "0.011"
                ],
                [
                    "25000.0",
                    "0.0009"
                ],
                [
                    "25335.32",
                    "0.0003"
                ],
                [
                    "32000.0",
                    "0.05"
                ]
            ],
            "bids": [
                [
                    "23490.0",
                    "0.0008"
                ],
                [
                    "22721.23",
                    "0.0011"
                ],
                [
                    "22721.21",
                    "0.0073"
                ],
                [
                    "22000.0",
                    "0.0003"
                ],
                [
                    "21800.0",
                    "0.007"
                ],
                [
                    "21351.1",
                    "0.0083"
                ],
                [
                    "21247.4",
                    "0.0015"
                ],
                [
                    "20512.98",
                    "0.053"
                ],
                [
                    "20000.0",
                    "0.0557"
                ],
                [
                    "3972.86",
                    "1.941"
                ],
                [
                    "2500.0",
                    "0.11"
                ],
                [
                    "2000.0",
                    "0.01"
                ],
                [
                    "100.0",
                    "2.0"
                ],
                [
                    "75.0",
                    "1.0"
                ],
                [
                    "70.0",
                    "0.04"
                ],
                [
                    "32.0",
                    "0.111"
                ],
                [
                    "20.0",
                    "2.304"
                ],
                [
                    "10.0",
                    "3.0"
                ]
            ]
        }
    }

The bid/ask of orderbook for `btcusdc` market alone is to be showed.

2. #### Graph
   You may use any graphing template like Trading View to implement the graphs (https://in.tradingview.com/widget/advanced-chart/)

## Bonus

- Feel free to add functionality (not mandatory)
- Use redux/context for state management
- Well explained readme (screenshot etc)

---
