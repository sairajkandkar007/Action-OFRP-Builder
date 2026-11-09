ihttps://account.xiaomi.com/fe/service/identity/authStart?sid=unlockApi&context=UbJreyzzHimkBAl2TrKJsrZUHbkhZEYxiUDCJfyJsBejTTkvKJmAw2_bqxr-lI_SFFolaJjl7iFfBmdmI8Ff-0KJgLcNjHIqo_# Build Recovery using Github Actions

- Support OrangeFox, [TWRP](https://github.com/azwhikaru/Action-TWRP-Builder) is here
- [中文说明](./README_CN.md)

---

## Thanks to
- All contributors

---

## Release Notes
```
= 2023/04/20
- The first available version is submitted.
```

-----

## Parameter Description

| Name | Description | Example |
| ------------ | -------------------- | ------------ |
| `SYNC_URL` | Script specified by OrangeFox | https://gitlab.com/OrangeFox/sync.git |
| `MANIFEST_BRANCH` | Source branch | 12.1                                                         |
| `DEVICE_TREE_URL` | Device address | https://github.com/OrangeFoxRecovery/device_xiaomi_laurel_sprout |
| `DEVICE_TREE_BRANCH` | Device branch | fox_12.1 |
| `DEVICE_PATH` | Device location | device/xiaomi/laurel_sprout |
| `COMMON_TREE_URL` | Common tree address |  |
| `COMMON_PATH` | Common tree location |  |
| `DEVICE_NAME` | Model name | laurel_sprout |
| `MAKEFILE_NAME` | Makefile name | twrp_laurel_sprout |
| `BUILD_TARGET` | Build Target Partition (boot/recovery/vendorboot) | recovery |

-----

## How to use
```
For example, your username is: JohnSmith
```
#### 1. Click 'Fork' in the upper right corner of this repository
![image](https://user-images.githubusercontent.com/37921907/177914706-c92476c5-7e14-4fb3-be94-0c8a11dae874.png)
#### 2. After waiting for the automatic redirection, you will see your own username
![image](https://user-images.githubusercontent.com/37921907/177915106-5bde6fc9-303c-479e-b290-22b48efd1e4e.png)
-----

## Building the Recovery
#### 9. Click 'Actions-Recovery Build'
![image](https://user-images.githubusercontent.com/37921907/177915304-8731ed80-1d49-48c9-9848-70d0ac8f2720.png)
#### 10. Click 'Run workflow' and fill in according to the above 'parameter description'
![image](https://user-images.githubusercontent.com/37921907/177915346-71c29149-78fb-4a00-996f-5d84ffc9eb8c.png)
#### 11. After filling in, click 'Run workflow' to start running

-----

## Compilation results
Can be downloaded at [Release](../../releases)

File not being uploaded to Release? Please check the step 'Check the output directory before uploading' and check the file name





Missing service data | Response: {'notificationUrl':
'https://account.xiaomi.com/fe/service/identity/authStart?sid=unlockApi&context=UbJreyzzHimkBAl2TrKJsrZUHbkhZEYxiUDCJfyJsBejTTkvKJmAw2_bqxr-lI_SFFolaJjl7iFfBmdmI8Ff-0KJgLcNjHIqo_J
vNQ2_w0IhGHbSasiSN6cP8DYR4d6R_TEcT83isJ1GaokEkYMi2ufJ81l1D9IY4aRv0Ni1lgTrJOP907oQfgthDkmCG4UnIXjF4C31e1WYbHJeJHSt4qlhCAtSwL8JhBOpY5jYPgXI7twJkjZpfIdhazTKbXzDEBsZWKNG5k2Vz6glzQeURx
-V6fwjaZmRltzXVxGZBuCB1_eSiWC1de0kevj0bQWuN42yI20gLQVFhWTKVD-vHVS6EshZv_zse-fqTJn0HZoMTg-SkjQGFIC74Q5Ko-69Vflmd7I67KR-BiImWe96jujsPiqbC18HVrvQnke39hcIRMywPtTPYjDUmpOGWoNq6iElrhhtX
H-fSGJMz91Z2hz_A8Cb6oLPxRAkVXEKwjXuMsYvKVi-5VMMmqMt6PSpou7H0LhQsK18GPmstWoZSaZeaaAEArtAcnt5ml2gNRekqoCxL4aFasUNbKKT2rBRgvpxSxxbARIcb1ciFAI5oK27D9MFlH0EGyNMxS66mYGJrWQEDSiUhupcIpc_
-DfNdN-VrMjtyQulC3UgBNjg8wUIm0pXDQvLmx20S8V_UCXiEj8hgE-AncYxEqyuGIwoLNOqzUSWUFeyoXyQiNP_H9iTmFAT2jTM7CLGFK2NNvv8bNAFGB69Uiri8HUEJ3dqIwu-p8hY-mRTbiVe6E9MBu_ZUUb9lzmX64HFtjoHi0k&_lo
cale=en', 'result': 'ok', 'code': 0, 'miDemo': 0, 'captchaUrl': None, 'description': '成功', 'location': '', 'securityStatus': 1, 'pwd': 0, 'child': 0, 'desc': '成功'}



