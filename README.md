# Thinkpad x280 - Hackintosh [Win 11/MacOS 12]

##### DualBoot with reFind - then OpenCore(to boot MacOS)

## ⚠️ Disclaimer

This is based on [0x8008 config for his x280](https://github.com/0x8008/x280-hackintosh).

Other config that also worked is [kushwavez config for his Thinkpad X1 Carbon 6th gen](https://github.com/kushwavez/lenovo-x1c6-clover-efi), i added some kexts and modifing config.plist to made it work almost close to 100%, except that bluetooth is not workin g (maybe needs some config in config.plist), in a future i will probably convert this config to OpenCore, buz both thunderbolt ports are workking giving video, while in other config, just only one port works, but as i said, it might be in a future, if you are interested in making the conversion your're welcome.

Meanwhile, im using a configuration based on [0x8008 hackintosh](https://github.com/0x8008/x280-hackintosh).

#### This is not a guide, it might be helpful for those who want to hackintosh their x280 (or laptop with similar hardware), trying this configs and applying may work or may require a bit of some configuration or kexts.

#### This is only for the Lenovo ThinkPad X280. I am NOT responsible for any harm you cause to your device.

---

<details><summary><strong>Hardware</strong></summary>

| Component | Description                   |
| --------- | ----------------------------- |
| CPU       | Intel Core i5-8250U           |
| GPU       | Intel UHD Graphics 620        |
| RAM       | 8GB 2400 Mhz                  |
| Wifi / BT | Intel Wireless-AC 8265        |
| Storage   | KXG50ZNV512G TOSHIBA M.2 Nvme |

</details>

<details><summary><strong>Software</strong></summary>

| Component       | Description |
| --------------- | ----------- |
| MacOS Monterrey | 12.6.7      |
| OpenCore        | 0.9.3       |
| reFind          | 0.12.0      |

</details>

## Status

<details>

<summary><strong>What's working ✅</strong></summary>

- [x] Almost everything

</details>

<details>

<summary><strong>What's not working ⚠️</strong></summary>

- [ ] Fingerprint reader `disabled in bios,  not an important missing feature to me`

- [ ] Samsung SSD's `i didnt own one, but almost everyone says , still unstable`

- [ ] Both thunderbolt `i mean, just the thunderbolt of power port works for video and usb hub at the same time, the other port just work for usb hub, but doesnt send video` _BUT with the [kushwavez config for his Thinkpad X1 Carbon 6th gen](https://github.com/kushwavez/lenovo-x1c6-clover-efi), both thunderbolts video works, i dont remember if hub works also in both (obviusly works in one of them), as i said, maybe in a future y covert his clover to OC and dualboot with reFind, for a better and stable experience_

</details>

<details>

<summary><strong>Untested</strong></summary>

- [ ] LTE slot `No device to test. i dont use it`
- [ ] eGPU `i dont know if a gaming box or an aliexpress DIY might work in macOS`

</details>

<details>

<summary><strong>Future Upgrades?</strong></summary>

- [ ] Screen `stock screen is i376x768. upgradable to 1980x1080p`
- [ ] Keyboard `a new one with BL`
- [ ] Battery `this one health is at 53% and 470 cicles`
- [ ] Wifi/BT Card `to BCM94360CS2 need to see if card if compatible`

</details>

## ⭐️ Feedback

Did you find any bugs or just have some questions? Feel free to provide your feedback using the Discussions tab.
