<h2 align=center>PoP mining within Hemi Network</h2>

## VPS Configuration

- You can start PoP mining either using VPS - Ubuntu 22.04
- RAM : 2 GB, Storage : 50 GB, CPU : 2 Core

## Installation

```bash
[ -f "hemixyz.sh" ] && rm hemixyz.sh; wget -q https://raw.githubusercontent.com/pvsairam/hemi-node/main/hemixyz.sh && chmod +x hemixyz.sh && ./hemixyz.sh
```

- If you want to check logs, use the below command

```bash
screen -r hemipop
```

![photo_6293956161048790638_y](https://github.com/user-attachments/assets/9ea27118-8a15-43ae-b5e8-abd1622197bc)

- If you see something like this 👆, it's fine

- If you see similar logs with errors/warnings, then don't worry, it is due to gas price fluctuation
- After that, make sure to detach from the screen session using `Ctrl` + `A` + `D`
- If you want to check your wallet details later, use the below command

```bash
cat ~/popm-address.json
```

## Reward

- TBA
- To check tHEMI you can use this [block explorer](https://testnet.explorer.hemi.xyz/)

![image](https://github.com/user-attachments/assets/af5fcf19-167b-44e8-b271-dc52363cdda4)
