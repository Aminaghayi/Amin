{
  "outbounds": 
  [
    {
      "type": "wireguard",
      "tag": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:830d:e7d:a110:3c2b:cf7c/128"
      ],
      "aB29+6GEsUpkx8nVt7wSKSvXcb1Aik5ZH6xopO2GgVs=",
      "server": "162.159.192.11",
      "server_port": 1070,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [199,83,69],
      "mtu": 1280,
      "fake_packets": "5-10"
    },
    {
      "type": "wireguard",
      "tag": "Warp-Main",
      "detour": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:89bd:ae34:17ae:57d5:8572/128"
      ],
      "private_key": "CCgkf9ZhlAS7TqVmtHBzd9cWr3OTn+hophMH0SNjylQ=",
      "server": "162.159.192.11",
      "server_port": 1070,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [159,8,192],
      "mtu": 1280,
      "fake_packets": "5-10"
    }
  ]
}
