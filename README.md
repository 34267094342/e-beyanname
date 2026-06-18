# e-beyanname

SAP Git-Enabled CTS (gCTS) Repository - E-Beyanname ABAP Package

## Açıklama

Bu repository, SAP S/4HANA Cloud sisteminde Git-Enabled Change and Transport System (gCTS) ile kullanılmak üzere oluşturulmuştur. E-Beyanname ürününe ait ABAP geliştirmelerini içermektedir.

## Sistem Bilgileri

- **SAP Sistemi:** S/4HANA Cloud - Partner Demo Development
- **System ID:** XI1 / vSID: 1GT
- **Repository Tipi:** GITHUB (gCTS)
- **Görünürlük:** Public

## Paket Bilgileri

- **ABAP Paketi:** E-Beyanname
- **Rol:** Development
- **Transport Katmanı:** gCTS yönetimli

## Klasör Yapısı

```
e-beyanname/
├── src/   ← ABAP nesneleri (gCTS tarafından yönetilir)
└── README.md
```

## Kullanım

Bu repository SAP gCTS tarafından otomatik olarak yönetilmektedir.

- ABAP geliştirmeleri SAP sisteminde yapılır
- Transport Request release edildiğinde gCTS otomatik commit atar
- Hedef sistemde Pull/Import ile değişiklikler alınır
