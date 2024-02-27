{
  "outbounds": 
  [
    {
      "type": "wireguard",
      "tag": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:8fa5:7f3:e31b:7810:c23/128"
      ],
      "private_key": "6A8IRcQTAWoU77vQvR2rQ4BT9v5Ks2guRlJOQWCEuXg=",
      "server": "188.114.97.255",
      "server_port": 928,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [ 24, 54, 157 ],
      "mtu": 1280,
      "fake_packets": "5-10"
    },
    {
      "type": "wireguard",
      "tag": "Warp-Main",
      "detour": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:8423:6627:c1a1:96c3:12c8/128"
      ],
      "private_key": "UD7HTPWG+tFW7zeMR4E18ucWDZBM02wfnR50JjRiiXo=",
      "server": "188.114.97.255",
      "server_port": 928,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [ 175, 240, 157 ],
      "mtu": 1280,
      "fake_packets": "5-10"
    }
  ]
}
