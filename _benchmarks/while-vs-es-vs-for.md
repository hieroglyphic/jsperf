---
title: while vs es vs for
setup: |
  const odds = {
      "cards": [],
      "round_name": "Bet",
      "lottery_event_id": 5,
      "round_id": 1,
      "is_maintenance": false,
      "seconds_left": 56,
      "maintenance_duration": 0,
      "run_id": "770416",
      "draw_code": "31702140174",
      "is_returned": 0,
      "hands_scores": false,
      "last_cards": [
  {
      "id": "314",
      "suit": "clubs",
      "value": "a"
  },
  {
      "id": "212",
      "suit": "hearts",
      "value": "q"
  },
  {
      "id": "413",
      "suit": "diamonds",
      "value": "k"
  },
  {
      "id": "404",
      "suit": "diamonds",
      "value": "4"
  },
  {
      "id": "306",
      "suit": "clubs",
      "value": "6"
  },
  {
      "id": "407",
      "suit": "diamonds",
      "value": "7"
  },
  {
      "id": "208",
      "suit": "hearts",
      "value": "8"
  },
  {
      "id": "113",
      "suit": "spades",
      "value": "k"
  },
  {
      "id": "213",
      "suit": "hearts",
      "value": "k"
  },
  {
      "id": "104",
      "suit": "spades",
      "value": "4"
  },
  {
      "id": "109",
      "suit": "spades",
      "value": "9"
  },
  {
      "id": "411",
      "suit": "diamonds",
      "value": "j"
  },
  {
      "id": "408",
      "suit": "diamonds",
      "value": "8"
  },
  {
      "id": "308",
      "suit": "clubs",
      "value": "8"
  },
  {
      "id": "309",
      "suit": "clubs",
      "value": "9"
  },
  {
      "id": "206",
      "suit": "hearts",
      "value": "6"
  },
  {
      "id": "305",
      "suit": "clubs",
      "value": "5"
  }
      ],
      "odds": [
  {
      "odd_id": "446",
      "odd_preset_id": 34,
      "odd_value": "5.05",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "1",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "447",
      "odd_preset_id": 34,
      "odd_value": "4.05",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "1",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "448",
      "odd_preset_id": 34,
      "odd_value": "3.35",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "3",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "449",
      "odd_preset_id": 34,
      "odd_value": "5.05",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "4",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "450",
      "odd_preset_id": 34,
      "odd_value": "5.05",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "5",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "451",
      "odd_preset_id": 34,
      "odd_value": "2.35",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "6",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "459",
      "odd_preset_id": 34,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "460",
      "odd_preset_id": 34,
      "odd_value": "5.60",
      "odd_value_real": 560,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.60",
      "odd_value_fractional": "23/5",
      "odd_value_american": "460",
      "odd_value_hongkong": "4.60"
  },
  {
      "odd_id": "461",
      "odd_preset_id": 34,
      "odd_value": "3.03",
      "odd_value_real": 303,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "3.03",
      "odd_value_fractional": "59/29",
      "odd_value_american": "203",
      "odd_value_hongkong": "2.03"
  },
  {
      "odd_id": "462",
      "odd_preset_id": 34,
      "odd_value": "6.60",
      "odd_value_real": 660,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "6.60",
      "odd_value_fractional": "28/5",
      "odd_value_american": "560",
      "odd_value_hongkong": "5.60"
  },
  {
      "odd_id": "463",
      "odd_preset_id": 34,
      "odd_value": "5.50",
      "odd_value_real": 550,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.50",
      "odd_value_fractional": "9/2",
      "odd_value_american": "450",
      "odd_value_hongkong": "4.50"
  },
  {
      "odd_id": "464",
      "odd_preset_id": 34,
      "odd_value": "8.40",
      "odd_value_real": 840,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "8.40",
      "odd_value_fractional": "37/5",
      "odd_value_american": "740",
      "odd_value_hongkong": "7.40"
  },
  {
      "odd_id": "465",
      "odd_preset_id": 34,
      "odd_value": "8.40",
      "odd_value_real": 840,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "8.40",
      "odd_value_fractional": "37/5",
      "odd_value_american": "740",
      "odd_value_hongkong": "7.40"
  },
  {
      "odd_id": "466",
      "odd_preset_id": 34,
      "odd_value": "80.00",
      "odd_value_real": 8000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "80.00",
      "odd_value_fractional": "79/1",
      "odd_value_american": "7900",
      "odd_value_hongkong": "79.00"
  },
  {
      "odd_id": "467",
      "odd_preset_id": 34,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "468",
      "odd_preset_id": 34,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "446",
      "odd_preset_id": 40,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "447",
      "odd_preset_id": 40,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "448",
      "odd_preset_id": 40,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "449",
      "odd_preset_id": 40,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "450",
      "odd_preset_id": 40,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "451",
      "odd_preset_id": 40,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "459",
      "odd_preset_id": 40,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "460",
      "odd_preset_id": 40,
      "odd_value": "5.50",
      "odd_value_real": 550,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.50",
      "odd_value_fractional": "9/2",
      "odd_value_american": "450",
      "odd_value_hongkong": "4.50"
  },
  {
      "odd_id": "461",
      "odd_preset_id": 40,
      "odd_value": "2.97",
      "odd_value_real": 297,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "2.97",
      "odd_value_fractional": "57/29",
      "odd_value_american": "197",
      "odd_value_hongkong": "1.97"
  },
  {
      "odd_id": "462",
      "odd_preset_id": 40,
      "odd_value": "6.45",
      "odd_value_real": 645,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "6.45",
      "odd_value_fractional": "60/11",
      "odd_value_american": "545",
      "odd_value_hongkong": "5.45"
  },
  {
      "odd_id": "463",
      "odd_preset_id": 40,
      "odd_value": "5.35",
      "odd_value_real": 535,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.35",
      "odd_value_fractional": "74/17",
      "odd_value_american": "435",
      "odd_value_hongkong": "4.35"
  },
  {
      "odd_id": "464",
      "odd_preset_id": 40,
      "odd_value": "8.25",
      "odd_value_real": 825,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "8.25",
      "odd_value_fractional": "29/4",
      "odd_value_american": "725",
      "odd_value_hongkong": "7.25"
  },
  {
      "odd_id": "465",
      "odd_preset_id": 40,
      "odd_value": "8.20",
      "odd_value_real": 820,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "8.20",
      "odd_value_fractional": "36/5",
      "odd_value_american": "720",
      "odd_value_hongkong": "7.20"
  },
  {
      "odd_id": "466",
      "odd_preset_id": 40,
      "odd_value": "80.00",
      "odd_value_real": 8000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "80.00",
      "odd_value_fractional": "79/1",
      "odd_value_american": "7900",
      "odd_value_hongkong": "79.00"
  },
  {
      "odd_id": "467",
      "odd_preset_id": 40,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "468",
      "odd_preset_id": 40,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "446",
      "odd_preset_id": 41,
      "odd_value": "5.20",
      "odd_value_real": 520,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.20",
      "odd_value_fractional": "21/5",
      "odd_value_american": "420",
      "odd_value_hongkong": "4.20"
  },
  {
      "odd_id": "447",
      "odd_preset_id": 41,
      "odd_value": "5.20",
      "odd_value_real": 520,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.20",
      "odd_value_fractional": "21/5",
      "odd_value_american": "420",
      "odd_value_hongkong": "4.20"
  },
  {
      "odd_id": "448",
      "odd_preset_id": 41,
      "odd_value": "5.20",
      "odd_value_real": 520,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.20",
      "odd_value_fractional": "21/5",
      "odd_value_american": "420",
      "odd_value_hongkong": "4.20"
  },
  {
      "odd_id": "449",
      "odd_preset_id": 41,
      "odd_value": "5.20",
      "odd_value_real": 520,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.20",
      "odd_value_fractional": "21/5",
      "odd_value_american": "420",
      "odd_value_hongkong": "4.20"
  },
  {
      "odd_id": "450",
      "odd_preset_id": 41,
      "odd_value": "5.20",
      "odd_value_real": 520,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.20",
      "odd_value_fractional": "21/5",
      "odd_value_american": "420",
      "odd_value_hongkong": "4.20"
  },
  {
      "odd_id": "451",
      "odd_preset_id": 41,
      "odd_value": "5.20",
      "odd_value_real": 520,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.20",
      "odd_value_fractional": "21/5",
      "odd_value_american": "420",
      "odd_value_hongkong": "4.20"
  },
  {
      "odd_id": "459",
      "odd_preset_id": 41,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "460",
      "odd_preset_id": 41,
      "odd_value": "5.80",
      "odd_value_real": 580,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.80",
      "odd_value_fractional": "24/5",
      "odd_value_american": "480",
      "odd_value_hongkong": "4.80"
  },
  {
      "odd_id": "461",
      "odd_preset_id": 41,
      "odd_value": "3.13",
      "odd_value_real": 313,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "3.13",
      "odd_value_fractional": "17/8",
      "odd_value_american": "213",
      "odd_value_hongkong": "2.13"
  },
  {
      "odd_id": "462",
      "odd_preset_id": 41,
      "odd_value": "6.80",
      "odd_value_real": 680,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "6.80",
      "odd_value_fractional": "29/5",
      "odd_value_american": "580",
      "odd_value_hongkong": "5.80"
  },
  {
      "odd_id": "463",
      "odd_preset_id": 41,
      "odd_value": "5.65",
      "odd_value_real": 565,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.65",
      "odd_value_fractional": "79/17",
      "odd_value_american": "465",
      "odd_value_hongkong": "4.65"
  },
  {
      "odd_id": "464",
      "odd_preset_id": 41,
      "odd_value": "8.70",
      "odd_value_real": 870,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "8.70",
      "odd_value_fractional": "77/10",
      "odd_value_american": "770",
      "odd_value_hongkong": "7.70"
  },
  {
      "odd_id": "465",
      "odd_preset_id": 41,
      "odd_value": "8.65",
      "odd_value_real": 865,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "8.65",
      "odd_value_fractional": "130/17",
      "odd_value_american": "765",
      "odd_value_hongkong": "7.65"
  },
  {
      "odd_id": "466",
      "odd_preset_id": 41,
      "odd_value": "80.00",
      "odd_value_real": 8000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "80.00",
      "odd_value_fractional": "79/1",
      "odd_value_american": "7900",
      "odd_value_hongkong": "79.00"
  },
  {
      "odd_id": "467",
      "odd_preset_id": 41,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "468",
      "odd_preset_id": 41,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "446",
      "odd_preset_id": 46,
      "odd_value": "4.40",
      "odd_value_real": 440,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.40",
      "odd_value_fractional": "17/5",
      "odd_value_american": "340",
      "odd_value_hongkong": "3.40"
  },
  {
      "odd_id": "447",
      "odd_preset_id": 46,
      "odd_value": "4.40",
      "odd_value_real": 440,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.40",
      "odd_value_fractional": "17/5",
      "odd_value_american": "340",
      "odd_value_hongkong": "3.40"
  },
  {
      "odd_id": "448",
      "odd_preset_id": 46,
      "odd_value": "4.40",
      "odd_value_real": 440,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.40",
      "odd_value_fractional": "17/5",
      "odd_value_american": "340",
      "odd_value_hongkong": "3.40"
  },
  {
      "odd_id": "449",
      "odd_preset_id": 46,
      "odd_value": "4.40",
      "odd_value_real": 440,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.40",
      "odd_value_fractional": "17/5",
      "odd_value_american": "340",
      "odd_value_hongkong": "3.40"
  },
  {
      "odd_id": "450",
      "odd_preset_id": 46,
      "odd_value": "4.40",
      "odd_value_real": 440,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.40",
      "odd_value_fractional": "17/5",
      "odd_value_american": "340",
      "odd_value_hongkong": "3.40"
  },
  {
      "odd_id": "451",
      "odd_preset_id": 46,
      "odd_value": "4.40",
      "odd_value_real": 440,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.40",
      "odd_value_fractional": "17/5",
      "odd_value_american": "340",
      "odd_value_hongkong": "3.40"
  },
  {
      "odd_id": "459",
      "odd_preset_id": 46,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "460",
      "odd_preset_id": 46,
      "odd_value": "4.91",
      "odd_value_real": 491,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.91",
      "odd_value_fractional": "43/11",
      "odd_value_american": "391",
      "odd_value_hongkong": "3.91"
  },
  {
      "odd_id": "461",
      "odd_preset_id": 46,
      "odd_value": "2.64",
      "odd_value_real": 264,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "2.64",
      "odd_value_fractional": "18/11",
      "odd_value_american": "164",
      "odd_value_hongkong": "1.64"
  },
  {
      "odd_id": "462",
      "odd_preset_id": 46,
      "odd_value": "5.75",
      "odd_value_real": 575,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.75",
      "odd_value_fractional": "19/4",
      "odd_value_american": "475",
      "odd_value_hongkong": "4.75"
  },
  {
      "odd_id": "463",
      "odd_preset_id": 46,
      "odd_value": "4.79",
      "odd_value_real": 479,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.79",
      "odd_value_fractional": "53/14",
      "odd_value_american": "379",
      "odd_value_hongkong": "3.79"
  },
  {
      "odd_id": "464",
      "odd_preset_id": 46,
      "odd_value": "7.30",
      "odd_value_real": 730,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "7.30",
      "odd_value_fractional": "63/10",
      "odd_value_american": "630",
      "odd_value_hongkong": "6.30"
  },
  {
      "odd_id": "465",
      "odd_preset_id": 46,
      "odd_value": "7.30",
      "odd_value_real": 730,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "7.30",
      "odd_value_fractional": "63/10",
      "odd_value_american": "630",
      "odd_value_hongkong": "6.30"
  },
  {
      "odd_id": "466",
      "odd_preset_id": 46,
      "odd_value": "70.00",
      "odd_value_real": 7000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "70.00",
      "odd_value_fractional": "69/1",
      "odd_value_american": "6900",
      "odd_value_hongkong": "69.00"
  },
  {
      "odd_id": "467",
      "odd_preset_id": 46,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "468",
      "odd_preset_id": 46,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "446",
      "odd_preset_id": 47,
      "odd_value": "5.05",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "405",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "447",
      "odd_preset_id": 47,
      "odd_value": "5.05",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "405",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "448",
      "odd_preset_id": 47,
      "odd_value": "5.05",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "405",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "449",
      "odd_preset_id": 47,
      "odd_value": "5.05",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "405",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "450",
      "odd_preset_id": 47,
      "odd_value": "5.05",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "405",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "451",
      "odd_preset_id": 47,
      "odd_value": "5.05",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "405",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "459",
      "odd_preset_id": 47,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "460",
      "odd_preset_id": 47,
      "odd_value": "5.60",
      "odd_value_real": 560,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.60",
      "odd_value_fractional": "23/5",
      "odd_value_american": "460",
      "odd_value_hongkong": "4.60"
  },
  {
      "odd_id": "461",
      "odd_preset_id": 47,
      "odd_value": "3.03",
      "odd_value_real": 303,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "3.03",
      "odd_value_fractional": "59/29",
      "odd_value_american": "203",
      "odd_value_hongkong": "2.03"
  },
  {
      "odd_id": "462",
      "odd_preset_id": 47,
      "odd_value": "6.60",
      "odd_value_real": 660,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "6.60",
      "odd_value_fractional": "28/5",
      "odd_value_american": "560",
      "odd_value_hongkong": "5.60"
  },
  {
      "odd_id": "463",
      "odd_preset_id": 47,
      "odd_value": "5.50",
      "odd_value_real": 550,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.50",
      "odd_value_fractional": "9/2",
      "odd_value_american": "450",
      "odd_value_hongkong": "4.50"
  },
  {
      "odd_id": "464",
      "odd_preset_id": 47,
      "odd_value": "8.40",
      "odd_value_real": 840,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "8.40",
      "odd_value_fractional": "37/5",
      "odd_value_american": "740",
      "odd_value_hongkong": "7.40"
  },
  {
      "odd_id": "465",
      "odd_preset_id": 47,
      "odd_value": "8.40",
      "odd_value_real": 840,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "8.40",
      "odd_value_fractional": "37/5",
      "odd_value_american": "740",
      "odd_value_hongkong": "7.40"
  },
  {
      "odd_id": "466",
      "odd_preset_id": 47,
      "odd_value": "80.00",
      "odd_value_real": 8000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "80.00",
      "odd_value_fractional": "79/1",
      "odd_value_american": "7900",
      "odd_value_hongkong": "79.00"
  },
  {
      "odd_id": "467",
      "odd_preset_id": 47,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "468",
      "odd_preset_id": 47,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "446",
      "odd_preset_id": 51,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "447",
      "odd_preset_id": 51,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "448",
      "odd_preset_id": 51,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "449",
      "odd_preset_id": 51,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "450",
      "odd_preset_id": 51,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "451",
      "odd_preset_id": 51,
      "odd_value": "4.95",
      "odd_value_real": 495,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.95",
      "odd_value_fractional": "75/19",
      "odd_value_american": "395",
      "odd_value_hongkong": "3.95"
  },
  {
      "odd_id": "459",
      "odd_preset_id": 51,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "460",
      "odd_preset_id": 51,
      "odd_value": "5.50",
      "odd_value_real": 550,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.50",
      "odd_value_fractional": "9/2",
      "odd_value_american": "450",
      "odd_value_hongkong": "4.50"
  },
  {
      "odd_id": "461",
      "odd_preset_id": 51,
      "odd_value": "2.97",
      "odd_value_real": 297,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "2.97",
      "odd_value_fractional": "57/29",
      "odd_value_american": "192",
      "odd_value_hongkong": "1.97"
  },
  {
      "odd_id": "462",
      "odd_preset_id": 51,
      "odd_value": "6.45",
      "odd_value_real": 645,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "6.45",
      "odd_value_fractional": "60/11",
      "odd_value_american": "545",
      "odd_value_hongkong": "5.45"
  },
  {
      "odd_id": "463",
      "odd_preset_id": 51,
      "odd_value": "5.35",
      "odd_value_real": 535,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.35",
      "odd_value_fractional": "74/17",
      "odd_value_american": "435",
      "odd_value_hongkong": "4.35"
  },
  {
      "odd_id": "464",
      "odd_preset_id": 51,
      "odd_value": "8.25",
      "odd_value_real": 825,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "8.25",
      "odd_value_fractional": "29/4",
      "odd_value_american": "725",
      "odd_value_hongkong": "7.25"
  },
  {
      "odd_id": "465",
      "odd_preset_id": 51,
      "odd_value": "8.20",
      "odd_value_real": 820,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "8.20",
      "odd_value_fractional": "36/5",
      "odd_value_american": "720",
      "odd_value_hongkong": "7.20"
  },
  {
      "odd_id": "466",
      "odd_preset_id": 51,
      "odd_value": "80.00",
      "odd_value_real": 8000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "80.00",
      "odd_value_fractional": "79/1",
      "odd_value_american": "7900",
      "odd_value_hongkong": "79.00"
  },
  {
      "odd_id": "467",
      "odd_preset_id": 51,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "468",
      "odd_preset_id": 51,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "446",
      "odd_preset_id": 56,
      "odd_value": "4.67",
      "odd_value_real": 467,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.67",
      "odd_value_fractional": "11/3",
      "odd_value_american": "367",
      "odd_value_hongkong": "3.67"
  },
  {
      "odd_id": "447",
      "odd_preset_id": 56,
      "odd_value": "4.67",
      "odd_value_real": 467,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.67",
      "odd_value_fractional": "11/3",
      "odd_value_american": "367",
      "odd_value_hongkong": "3.67"
  },
  {
      "odd_id": "448",
      "odd_preset_id": 56,
      "odd_value": "4.67",
      "odd_value_real": 467,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.67",
      "odd_value_fractional": "11/3",
      "odd_value_american": "367",
      "odd_value_hongkong": "3.67"
  },
  {
      "odd_id": "449",
      "odd_preset_id": 56,
      "odd_value": "4.67",
      "odd_value_real": 467,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.67",
      "odd_value_fractional": "11/3",
      "odd_value_american": "367",
      "odd_value_hongkong": "3.67"
  },
  {
      "odd_id": "450",
      "odd_preset_id": 56,
      "odd_value": "4.67",
      "odd_value_real": 467,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.67",
      "odd_value_fractional": "11/3",
      "odd_value_american": "367",
      "odd_value_hongkong": "3.67"
  },
  {
      "odd_id": "451",
      "odd_preset_id": 56,
      "odd_value": "4.67",
      "odd_value_real": 467,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "4.67",
      "odd_value_fractional": "11/3",
      "odd_value_american": "367",
      "odd_value_hongkong": "3.67"
  },
  {
      "odd_id": "459",
      "odd_preset_id": 56,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "460",
      "odd_preset_id": 56,
      "odd_value": "5.20",
      "odd_value_real": 520,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.20",
      "odd_value_fractional": "21/5",
      "odd_value_american": "420",
      "odd_value_hongkong": "4.20"
  },
  {
      "odd_id": "461",
      "odd_preset_id": 56,
      "odd_value": "2.80",
      "odd_value_real": 280,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "2.80",
      "odd_value_fractional": "9/5",
      "odd_value_american": "180",
      "odd_value_hongkong": "1.80"
  },
  {
      "odd_id": "462",
      "odd_preset_id": 56,
      "odd_value": "6.10",
      "odd_value_real": 610,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "6.10",
      "odd_value_fractional": "51/10",
      "odd_value_american": "510",
      "odd_value_hongkong": "5.10"
  },
  {
      "odd_id": "463",
      "odd_preset_id": 56,
      "odd_value": "5.05",
      "odd_value_real": 505,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "5.05",
      "odd_value_fractional": "77/19",
      "odd_value_american": "405",
      "odd_value_hongkong": "4.05"
  },
  {
      "odd_id": "464",
      "odd_preset_id": 56,
      "odd_value": "7.80",
      "odd_value_real": 780,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "7.80",
      "odd_value_fractional": "34/5",
      "odd_value_american": "680",
      "odd_value_hongkong": "6.80"
  },
  {
      "odd_id": "465",
      "odd_preset_id": 56,
      "odd_value": "7.75",
      "odd_value_real": 775,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "7.75",
      "odd_value_fractional": "27/4",
      "odd_value_american": "675",
      "odd_value_hongkong": "6.75"
  },
  {
      "odd_id": "466",
      "odd_preset_id": 56,
      "odd_value": "75.00",
      "odd_value_real": 7500,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "75.00",
      "odd_value_fractional": "74/1",
      "odd_value_american": "7400",
      "odd_value_hongkong": "74.00"
  },
  {
      "odd_id": "467",
      "odd_preset_id": 56,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  },
  {
      "odd_id": "468",
      "odd_preset_id": 56,
      "odd_value": "100.00",
      "odd_value_real": 10000,
      "status": "active",
      "is_enabled": "1",
      "odd_class": "",
      "odd_value_decimal": "100.00",
      "odd_value_fractional": "99/1",
      "odd_value_american": "9900",
      "odd_value_hongkong": "99.00"
  }
      ],
      "won_odds": false,
      "push_odds": false,
      "results": {
      "winners_hand": [
      6
      ],
      "winner_combination": 5,
      "winner_cards": [
      [
  {
      "id": "411",
      "suit": "diamonds",
      "value": "j"
  },
  {
      "id": "407",
      "suit": "diamonds",
      "value": "7"
  }
      ]
      ],
      "table_cards": [
  {
      "id": "408",
      "suit": "diamonds",
      "value": "8"
  },
  {
      "id": "308",
      "suit": "clubs",
      "value": "8"
  },
  {
      "id": "309",
      "suit": "clubs",
      "value": "9"
  },
  {
      "id": "206",
      "suit": "hearts",
      "value": "6"
  },
  {
      "id": "305",
      "suit": "clubs",
      "value": "5"
  }
      ]
  },
      "info_time": 1487082244
  }.odds;
  
  const getPokerLeadersWhile = (odds) => {
      let handOdds = odds.splice(0, 6).map((odd, index) => {
          return {hand: index + 1, value: odd.odd_value_american, status: odd.status}
      }).sort((x, y) => x.value - y.value);
      let leadersCount = 0;
      let leaders = [[], [], []];
      let counter = 0;
      let lastResult = false;
      while (counter < handOdds.length) {
      if (handOdds[counter].status !== 'active') {
      counter++;
      continue;
  }
      if (lastResult && lastResult != handOdds[counter].value ) leadersCount++;
      if (leadersCount === 3) break;
      leaders[leadersCount].push(handOdds[counter].hand);
      lastResult = handOdds[counter].value;
      counter++;
  }
  
      return leaders;
  }
  
  const getPokerLeadersES = (odds) => {
      let handOdds = odds.slice(0, 6);
      let activeHandOdds = handOdds.filter((odd, index) => {
      odd.hand = index + 1
  
      return odd.status === 'active';
  });
      let firstLeaderHands = this.getLeaderHands(activeHandOdds);
      let secondLeaderHands = [];
      let thirdLeaderHands = [];
      if (firstLeaderHands.length === 1) {
      let secondActiveHandOdds = activeHandOdds.filter(odd => firstLeaderHands[0] !== odd.hand);
      secondLeaderHands = this.getLeaderHands(secondActiveHandOdds);
      let thirdActiveHandOdds = secondActiveHandOdds.filter(odd => secondLeaderHands[0] !== odd.hand);
      thirdLeaderHands = this.getLeaderHands(thirdActiveHandOdds);
  }
      return {firstLeaderHands, secondLeaderHands, thirdLeaderHands}
  }
      getLeaderHands(handOdds) {
      let handOddsValues = handOdds.map(odd => parseInt(odd.odd_value_american, 10));
      let minOddValue = Math.min(...handOddsValues);
      return handOdds.reduce((accumulator, odd) => {
      if (odd.odd_value_american == minOddValue) {
      accumulator.push(odd.hand);
  }
      return accumulator;
  }, []);
  }
  
  
  const getLeadersFor = (odds2) => {
      var odds = odds2.slice(0, 6);
      var firstLeader = {handNumbers: []};
      var secondLeader = {handNumbers: []};
      var thirdLeader = {handNumbers: []};
      odds.forEach(function(el, i) {
          if (el.status != 'active') continue;
  
          if (!firstLeader.handNumbers.length || firstLeader.handScore > el.odd_value_american){
              thirdLeader = secondLeader;
              secondLeader = firstLeader;
              firstLeader = {};
              firstLeader.handNumbers = [i];
              firstLeader.handScore = el.odd_value_american;
          } else if (firstLeader.handScore == el.odd_value_american) {
              firstLeader.handNumbers.push(i);
          } else if (!secondLeader.handNumbers.length || secondLeader.handScore > el.odd_value_american) {
              thirdLeader = secondLeader;
              secondLeader = {};
              secondLeader.handNumbers = [i];
              secondLeader.handScore = el.odd_value_american;
          } else if (secondLeader.handScore == el.odd_value_american) {
              secondLeader.handNumbers.push(i);
          } else if (!thirdLeader.handNumbers.length || thirdLeader.handScore > el.odd_value_american) {
              thirdLeader.handNumbers = [i];
              thirdLeader.handScore = el.odd_value_american;
          } else if (thirdLeader.handScore == el.odd_value_american) {
              thirdLeader.handNumbers.push(i);
          }
      });
  
      return {firstLeader, secondLeader, thirdLeader}
  }
tests:
  -
    name: while
    code: |
      getPokerLeadersWhile(odds);
  -
    name: es
    code: |
      getPokerLeadersES(odds)
  -
    name: for
    code: |
      getLeadersFor(odds)
---
Betgames code battle
