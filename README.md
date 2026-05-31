### Sequence Diagram

| No | Judul | Aktor |
|----|-------|-------|
| 1 | [Membuat Pesanan](#1-membuat-pesanan) | Kasir |
| 2 | [Menyimpan Pesanan](#2-menyimpan-pesanan) | Kasir |
| 3 | [Mencatat Pembayaran (Kasir)](#3-mencatat-pembayaran-kasir) | Kasir |
| 4 | [Melihat / Cetak Invoice](#4-melihatcetak-invoice) | Kasir |
| 5 | [Memproses Pengambilan Barang](#5-memproses-pengambilan-barang) | Kasir |
| 6 | [Mengelola Produk](#6-mengelola-produk) | Owner |
| 7 | [Mengelola Varian Produk](#7-mengelola-varian-produk) | Owner |
| 8 | [Mengelola Opsi Varian](#8-mengelola-opsi-varian) | Owner |
| 9 | [Mengelola Tipe Sablon](#9-mengelola-tipe-sablon) | Owner |
| 10 | [Mengelola Stok](#10-mengelola-stok) | Owner |
| 11 | [Mengelola Status Produksi / Pesanan](#11-mengelola-status-produksipesanan) | Owner |
| 12 | [Melihat Dashboard / Laporan](#12-melihat-dashboardlaporan) | Owner |
| 13 | [Mencatat Pembayaran (Owner)](#13-mencatat-pembayaran-owner) | Owner |
 
---

### 1. Membuat Pesanan
- [![Membuat Pesanan](https://www.plantuml.com/plantuml/png/RPBTQkCm48NlzHH3hbf8Ng0NIpTE2sKt4AZt0SRH99bQ7dcbKM7VViToJVe7lZ3wZkQSW-O-AoOjGt3A6WYUwMyXEH9iO4z3Lr3XG1a5nJayQapm2pCdryKY7jC_M3t6D9Xcc5Khm0n_djmnYgOOODKcb6mtEKepdmLALTKsZiHSRSOXHL-Eke-UGcM7lVEes64cMEtU_YhPRPsh4M3pmupW3hQbHxXWm045nYM8CsQAjZ55cafbXTCKzQemPeh3tXHdqfgX_zahdsvkdPqQsssDFJ_yVcXQ62jVmoicHbb373El8MCNeZWJRfPPKt2pF54YoLmdBK4gcWS1Jaurmr94SHWvzDPY2lgffH6-V0dXIP43iDBmNU4BQv7pZEUs5RzYO6_JWMKiUiMBLowTHiMtkHzpMCWEBz2JVVQqBoZdzyxeVHiRMwcRwUxjUzVCmsZTflFfUgQSRIa-62UMSu_sEf-66vzJt5q1U1ufTPWAktiIRply7m)](https://www.plantuml.com/plantuml/png/RPBTQkCm48NlzHH3hbf8Ng0NIpTE2sKt4AZt0SRH99bQ7dcbKM7VViToJVe7lZ3wZkQSW-O-AoOjGt3A6WYUwMyXEH9iO4z3Lr3XG1a5nJayQapm2pCdryKY7jC_M3t6D9Xcc5Khm0n_djmnYgOOODKcb6mtEKepdmLALTKsZiHSRSOXHL-Eke-UGcM7lVEes64cMEtU_YhPRPsh4M3pmupW3hQbHxXWm045nYM8CsQAjZ55cafbXTCKzQemPeh3tXHdqfgX_zahdsvkdPqQsssDFJ_yVcXQ62jVmoicHbb373El8MCNeZWJRfPPKt2pF54YoLmdBK4gcWS1Jaurmr94SHWvzDPY2lgffH6-V0dXIP43iDBmNU4BQv7pZEUs5RzYO6_JWMKiUiMBLowTHiMtkHzpMCWEBz2JVVQqBoZdzyxeVHiRMwcRwUxjUzVCmsZTflFfUgQSRIa-62UMSu_sEf-66vzJt5q1U1ufTPWAktiIRply7m)
 
---
 
### 2. Menyimpan Pesanan
- [![Menyimpan Pesanan](https://www.plantuml.com/plantuml/png/XLF1Rjim3BthAuYSDi3P1_GmD77ImHYS58bx3XY9M8J8aYjH1VBtevLuQu2rkn5yJu_FVFHZOeoSUwVOiYFOqsichmdcq9A_s7v03y-KqADN2ZM723ynsQYE8Nk3yGApfn1xg4-apo7p3331IwDqy1o3WraNqITvQ8Elhpr7iR2wMf6NiPSxKXiCkIlUAeECHqm4izMjAiXggLHn0VFlCWmUO9-FlMKORawb9qXN2vB4Cdq9qL0SDRugwKxO6pfhH0Vg_UwfWaGfYOCAZ7oqzKFcYTmAMKT2fkqez5Uk0Ytxgo0dYeqHyNRahvR2Nwv_D1leTelDVb5tpNRp7cms-_Mk0vt5Nayn_GChCpu43fQf_nmz66Aqxh-aP7_vEzBByshHhMKxqQBdGnZ6NDAtrumbhW_rv9OufyF9ZZk_ezNRjcqw9VLyMkVDWgbkbPRSovCfd9C4u_ua-YurxGZZ51PmEPrpieKotKCaOoDfbXZVWjLKBaB0wzKy06C_M7SkELy9Z-ID_0U_0G)](https://www.plantuml.com/plantuml/png/XLF1Rjim3BthAuYSDi3P1_GmD77ImHYS58bx3XY9M8J8aYjH1VBtevLuQu2rkn5yJu_FVFHZOeoSUwVOiYFOqsichmdcq9A_s7v03y-KqADN2ZM723ynsQYE8Nk3yGApfn1xg4-apo7p3331IwDqy1o3WraNqITvQ8Elhpr7iR2wMf6NiPSxKXiCkIlUAeECHqm4izMjAiXggLHn0VFlCWmUO9-FlMKORawb9qXN2vB4Cdq9qL0SDRugwKxO6pfhH0Vg_UwfWaGfYOCAZ7oqzKFcYTmAMKT2fkqez5Uk0Ytxgo0dYeqHyNRahvR2Nwv_D1leTelDVb5tpNRp7cms-_Mk0vt5Nayn_GChCpu43fQf_nmz66Aqxh-aP7_vEzBByshHhMKxqQBdGnZ6NDAtrumbhW_rv9OufyF9ZZk_ezNRjcqw9VLyMkVDWgbkbPRSovCfd9C4u_ua-YurxGZZ51PmEPrpieKotKCaOoDfbXZVWjLKBaB0wzKy06C_M7SkELy9Z-ID_0U_0G)
 
---
 
### 3. Mencatat Pembayaran Kasir
- [![Mencatat Pembayaran Kasir](https://www.plantuml.com/plantuml/png/ZLB1Ri8m3BtdAonE834-WCC4jDrKRIs8XZDocmWYqgHBqadz-vcMJaNQOQSaVi_FptOsFg0BRQrPK45BAEHNAqqbuGKoEZ5WW8EiI-pGeO4FzCenXbMmxl4eRMi4kWvciGoeDD4z6ZGpG0-db5NM16Srp3W9UCfKraH3J4lNitZ4fA7wtHCfiqBg0S-O82SbUabL7hSUYNUCzJRWvPMAmHfIqxG1cb_BZAA4yOWm9olhn06xcihDwIfTAfRG386xy88HSQH_erQ2n24gZcyWg7rZQsLGZwJiNvfBkDqTfeB4itjUlAEyNVAUvi2FsxpOHZpTvrCmpOlao4SHFuMAv3E9E1IdR3x2Awnf1s7n1wtturSN6eGu1nl8E-hfUA2MfD5U5GIyg2lD2s0YSph4MvwCClrnfXyJMl_CUnYU4ivNvUcNTBHQCNKMxRCivNra7FIZaRCI_MJ7LJhf6sjevxwzUUdxJH8sx7iDGvbfBq6w4btBDbIIllGF)](https://www.plantuml.com/plantuml/png/ZLB1Ri8m3BtdAonE834-WCC4jDrKRIs8XZDocmWYqgHBqadz-vcMJaNQOQSaVi_FptOsFg0BRQrPK45BAEHNAqqbuGKoEZ5WW8EiI-pGeO4FzCenXbMmxl4eRMi4kWvciGoeDD4z6ZGpG0-db5NM16Srp3W9UCfKraH3J4lNitZ4fA7wtHCfiqBg0S-O82SbUabL7hSUYNUCzJRWvPMAmHfIqxG1cb_BZAA4yOWm9olhn06xcihDwIfTAfRG386xy88HSQH_erQ2n24gZcyWg7rZQsLGZwJiNvfBkDqTfeB4itjUlAEyNVAUvi2FsxpOHZpTvrCmpOlao4SHFuMAv3E9E1IdR3x2Awnf1s7n1wtturSN6eGu1nl8E-hfUA2MfD5U5GIyg2lD2s0YSph4MvwCClrnfXyJMl_CUnYU4ivNvUcNTBHQCNKMxRCivNra7FIZaRCI_MJ7LJhf6sjevxwzUUdxJH8sx7iDGvbfBq6w4btBDbIIllGF)
 
---
 
### 4. Melihat/Cetak Invoice
- [![Melihat/Cetak Invoice](https://www.plantuml.com/plantuml/png/XL9DIyD04BtlhnXoKcZnteEKfe91WqBZMQR9M9ViHzoT2FdtJZO9MAnw6zvxCszuCzl86BYtHh5cGt2WZvvSJR26aen-Hxx9YR65mdrwNPDIMBCFy81H1tNqlMim393Teq6BRf5bW15U2bLxny4RoAg0BaghzYwVC4CXgQfSaHFpuKnK-eRCn9UgGSOZHe9iFrU9sU-KIdl0-bRCO0ExlaNGywQ225xbWi_GbGyDXQAvLeAEN2dSctRDquX_OykHtU-4FTmztkKL92gkeEuZUokb4dQzZ1ZtcoGN1nTCDlux_LMFiXKq4hSsgOZwv2uuZSABHiyuMCdoJwzkrlmSsv4zue1oWzIsP3TPJW628NTgiKlkI-Y1dBYTnIxKT9WDCDfEcrPUOn6SdwnEt_LBiy71zmnTq8xLLdpaKRy0)](https://www.plantuml.com/plantuml/png/XL9DIyD04BtlhnXoKcZnteEKfe91WqBZMQR9M9ViHzoT2FdtJZO9MAnw6zvxCszuCzl86BYtHh5cGt2WZvvSJR26aen-Hxx9YR65mdrwNPDIMBCFy81H1tNqlMim393Teq6BRf5bW15U2bLxny4RoAg0BaghzYwVC4CXgQfSaHFpuKnK-eRCn9UgGSOZHe9iFrU9sU-KIdl0-bRCO0ExlaNGywQ225xbWi_GbGyDXQAvLeAEN2dSctRDquX_OykHtU-4FTmztkKL92gkeEuZUokb4dQzZ1ZtcoGN1nTCDlux_LMFiXKq4hSsgOZwv2uuZSABHiyuMCdoJwzkrlmSsv4zue1oWzIsP3TPJW628NTgiKlkI-Y1dBYTnIxKT9WDCDfEcrPUOn6SdwnEt_LBiy71zmnTq8xLLdpaKRy0)
 
---
 
### 5. Memproses Pengambilan Barang
- [![Memproses Pengambilan Barang](https://www.plantuml.com/plantuml/png/TLBBJiCm4BpxArOzWQ1yG2LGcmSewbDDUgwsoIgrOZl1Tf3wzsppW1Q9aotlpEpihEVEe_MjLi9BhmXI-cp9v0HJM9DkREt8mOvCYVea5He8qA8fXS3SrnQMwAGLfxer1TeBJ2BoA1KJ71eq4q07XqJajV6sLZ39cEkOAMiJzc-AR8VAGb6WnnCwOfNXrbMYG8Yk3KpVM0nci5IoWi5QysjDS94XMSYGlDQD8ayxcLTjyr3RWcnIF0ekZf0lLB9WNGZJ_JiKF1hR8QYwYNfS530kY3-I3MJxnIPTX5cotTmMqtWLXnbq-i_Gu4MJyU1QhJaEmP3fs8vpzgthaLstXlG9BzSq1IhcNAyUF5aUgJrB0N3Jvx2B5bdSizrBTnm7nTUVOOjxJh99u_tWRG0VpzBnsYxtm72xNYVPy3Q6xDgAynMaU26ZDywh-i_XVhjQ1Ojm-KUcn18LF04gv2yXo1JTchZSxtG67dKZLSM9dFb5YJbZ-3z-0m)](https://www.plantuml.com/plantuml/png/TLBBJiCm4BpxArOzWQ1yG2LGcmSewbDDUgwsoIgrOZl1Tf3wzsppW1Q9aotlpEpihEVEe_MjLi9BhmXI-cp9v0HJM9DkREt8mOvCYVea5He8qA8fXS3SrnQMwAGLfxer1TeBJ2BoA1KJ71eq4q07XqJajV6sLZ39cEkOAMiJzc-AR8VAGb6WnnCwOfNXrbMYG8Yk3KpVM0nci5IoWi5QysjDS94XMSYGlDQD8ayxcLTjyr3RWcnIF0ekZf0lLB9WNGZJ_JiKF1hR8QYwYNfS530kY3-I3MJxnIPTX5cotTmMqtWLXnbq-i_Gu4MJyU1QhJaEmP3fs8vpzgthaLstXlG9BzSq1IhcNAyUF5aUgJrB0N3Jvx2B5bdSizrBTnm7nTUVOOjxJh99u_tWRG0VpzBnsYxtm72xNYVPy3Q6xDgAynMaU26ZDywh-i_XVhjQ1Ojm-KUcn18LF04gv2yXo1JTchZSxtG67dKZLSM9dFb5YJbZ-3z-0m)
 
---
 
### 6. Mengelola Produk
- [![Mengelola Produk](https://www.plantuml.com/plantuml/png/VL6xRiCm3Dpr5OIdTZ2oPoZIs2wGmQsHnmVG5fkubILNebBaxyl8TiPEadYdUu2RmEWv3aPnpuRWG3-HR4UGGqtsJCOPXCOx7R-LmewTXuzVIrwrBbgD_WPPZHQ_Q20xypB00AUTwfnbxmnaQTnnCRqD-SHe2aLMJ6yFGkqqcGchbKR65WD1LiwtX9HRfL80o5_41DPmnA75owhIFSCu1PMve4qXQC0hpV9FutJUzPwLe0ldYgRN67ee3litq6YXjsFaXLB_ArFVEULMEBltGxK_havD-NgiO6O59LY-o5p4nK3eXn5j-lg8oSWn9CUbbwSmEXiejP7Xr7ej-JvbPNDLOF8j-gWsPBLiyGy)](https://www.plantuml.com/plantuml/png/VL6xRiCm3Dpr5OIdTZ2oPoZIs2wGmQsHnmVG5fkubILNebBaxyl8TiPEadYdUu2RmEWv3aPnpuRWG3-HR4UGGqtsJCOPXCOx7R-LmewTXuzVIrwrBbgD_WPPZHQ_Q20xypB00AUTwfnbxmnaQTnnCRqD-SHe2aLMJ6yFGkqqcGchbKR65WD1LiwtX9HRfL80o5_41DPmnA75owhIFSCu1PMve4qXQC0hpV9FutJUzPwLe0ldYgRN67ee3litq6YXjsFaXLB_ArFVEULMEBltGxK_havD-NgiO6O59LY-o5p4nK3eXn5j-lg8oSWn9CUbbwSmEXiejP7Xr7ej-JvbPNDLOF8j-gWsPBLiyGy)
 
---
 
### 7. Mengelola Varian Produk
- [![Mengelola Varian Produk](https://www.plantuml.com/plantuml/png/VL6nJiCm4Dtz5QTCC5JTEw3I94Cb0X5DMT4blj9GnmxskQX_Zsid5InizhttxhsxMpj6otvGWdjM13lwygGxWWLKf3z86ONmXhP73RKrqf-4m8wDXPTlJLQqnck9zW9PXHe_QI0zqJD01_kjw8ncQnHaKTvndlwAR6JKkI0Tl2ytGcKagOHLGY9ZYuuWAwPNH8gD4340B1w22QoWmQ75uxAKFSCv1X2X7j0w3wZ3CwLOV9TGllQx5m6TEMTKlKJNGwz7ppDI_QkkhfnY4pYxygdC6nZJ34w4ucBMn-8f6VpMR9ztvMkptDV5OrFEqlV9uM-BOmYcmFN360QxjhXDniZUnRJpAYovqMX7SG6Xc1Qr0ec7SEnfEy1aMxHUh4dBSFyV)](https://www.plantuml.com/plantuml/png/VL6nJiCm4Dtz5QTCC5JTEw3I94Cb0X5DMT4blj9GnmxskQX_Zsid5InizhttxhsxMpj6otvGWdjM13lwygGxWWLKf3z86ONmXhP73RKrqf-4m8wDXPTlJLQqnck9zW9PXHe_QI0zqJD01_kjw8ncQnHaKTvndlwAR6JKkI0Tl2ytGcKagOHLGY9ZYuuWAwPNH8gD4340B1w22QoWmQ75uxAKFSCv1X2X7j0w3wZ3CwLOV9TGllQx5m6TEMTKlKJNGwz7ppDI_QkkhfnY4pYxygdC6nZJ34w4ucBMn-8f6VpMR9ztvMkptDV5OrFEqlV9uM-BOmYcmFN360QxjhXDniZUnRJpAYovqMX7SG6Xc1Qr0ec7SEnfEy1aMxHUh4dBSFyV)
 
---
 
### 8. Mengelola Opsi Varian
- [![Mengelola Opsi Varian](https://www.plantuml.com/plantuml/png/XP9FJyCm3CNl-HHMJo1jsfq36cjxc4HPnJgkaziQLfOc9N4tZK-FswmJd3ZbZtzvVdxAqZCwxbkjk65DiAMldan5C8UCp0Tfgn4sdM_W3Ls3HYcis3hOd0qvLThUrEWk46Ley9DQCh_X2D33RgqgQzXP3L7kRDrN78Up9ZSIUQp8IFlB3SXiJJhKCbKZOucU84gkkx6Ih9GQNS3yKPh00nJObdXOf7N3O0SNfs1PYeBaiI0UJnIyyQRZnfexEow3yhqIP09Fg9iQHQC_zWxD3Cxe3Cx0iprENFQ_O3Q0oKh0RVgSnWLqOS1ziCPU59jlagMosZglX9rFsiFWmSXleVNBDdqj5hiyUIhIwuYy3rt_lZ-8VotwRISX30gt51Yvz-COKtQEV2VlQGnBBaEoWuTt-I0XJYPNeklLaamjF-O7)](https://www.plantuml.com/plantuml/png/XP9FJyCm3CNl-HHMJo1jsfq36cjxc4HPnJgkaziQLfOc9N4tZK-FswmJd3ZbZtzvVdxAqZCwxbkjk65DiAMldan5C8UCp0Tfgn4sdM_W3Ls3HYcis3hOd0qvLThUrEWk46Ley9DQCh_X2D33RgqgQzXP3L7kRDrN78Up9ZSIUQp8IFlB3SXiJJhKCbKZOucU84gkkx6Ih9GQNS3yKPh00nJObdXOf7N3O0SNfs1PYeBaiI0UJnIyyQRZnfexEow3yhqIP09Fg9iQHQC_zWxD3Cxe3Cx0iprENFQ_O3Q0oKh0RVgSnWLqOS1ziCPU59jlagMosZglX9rFsiFWmSXleVNBDdqj5hiyUIhIwuYy3rt_lZ-8VotwRISX30gt51Yvz-COKtQEV2VlQGnBBaEoWuTt-I0XJYPNeklLaamjF-O7)
 
---
 
### 9. Mengelola Tipe Sablon
- [![Mengelola Tipe Sablon](https://www.plantuml.com/plantuml/png/TP8nRy8m48Lt_ufJfdP0tHag845L1eS8p8mkyHLIENPgNwZoxsiIWbZOplwUxzuzUHKOFVUj4Tom8JZGRq-s9bY097icumo2Qhf8i3BE2e4rEm-xFqjULAwt6lq0YKIBFzIIVHOdW06EkQYTPUyC9ALtkgyvdSw6_AWeKq4sZXyU0kaqcOb9eP6nma2GPFTg9Db6YD45B3xZ45Y2mhR2oyTMDmnySn4con56IPb6IS0hJTxKqD7RhVMxY6JcLpIDnj10OxkUPo9VlfGtdcqYtso_yWBKVbqSrgdATyKpp8l3Tgy-ZcMsLjkxhHF7Fk6rgaQci_F3wPKytKcPAn7hnMpo4gqR24tReHsbZxqPkG_ZFdDQdaBdRA0nddWvPRa4ZT_nIpm724o-Gj-B5LaTlye_)](https://www.plantuml.com/plantuml/png/TP8nRy8m48Lt_ufJfdP0tHag845L1eS8p8mkyHLIENPgNwZoxsiIWbZOplwUxzuzUHKOFVUj4Tom8JZGRq-s9bY097icumo2Qhf8i3BE2e4rEm-xFqjULAwt6lq0YKIBFzIIVHOdW06EkQYTPUyC9ALtkgyvdSw6_AWeKq4sZXyU0kaqcOb9eP6nma2GPFTg9Db6YD45B3xZ45Y2mhR2oyTMDmnySn4con56IPb6IS0hJTxKqD7RhVMxY6JcLpIDnj10OxkUPo9VlfGtdcqYtso_yWBKVbqSrgdATyKpp8l3Tgy-ZcMsLjkxhHF7Fk6rgaQci_F3wPKytKcPAn7hnMpo4gqR24tReHsbZxqPkG_ZFdDQdaBdRA0nddWvPRa4ZT_nIpm724o-Gj-B5LaTlye_)
 
---
 
### 10. Mengelola Stok
- [![Mengelola Stok](https://www.plantuml.com/plantuml/png/RP9DJiCm48NtFiKeAv0e1-W2bIQLg4H4KDerciIZrjIrKtiCulPCdGPHnCxnU--RdtWH6GEderLis1AqT4haUe8PrEHsPBr5QDaVbCAUVO2NJqT1TJuvZU4BYYUqU4INFGLWXErQzTvny1QA9dYTUYx7RqiXEvfIaPDoafPKVwYz9fkLjbOQ6JkC14LrEMMbMYgLIyFiGKh07BOTxk6KS2J5SujoBsfJYfe60T7hHRxn0nllrlhk9t6hn3UvFz0QZT60SKFY4JRARIqowlSKEVVwBqbCOgsMOcrNpwjo8y1WH7qRtL69Dfjevmbp2JXlxdTusrIFczNVyFrKw8gobtRjPSpCc6R9PARGOKXvY6bXWU8WECfhaijndNDWF0x67kGVNaKNvBIyYsy)](https://www.plantuml.com/plantuml/png/RP9DJiCm48NtFiKeAv0e1-W2bIQLg4H4KDerciIZrjIrKtiCulPCdGPHnCxnU--RdtWH6GEderLis1AqT4haUe8PrEHsPBr5QDaVbCAUVO2NJqT1TJuvZU4BYYUqU4INFGLWXErQzTvny1QA9dYTUYx7RqiXEvfIaPDoafPKVwYz9fkLjbOQ6JkC14LrEMMbMYgLIyFiGKh07BOTxk6KS2J5SujoBsfJYfe60T7hHRxn0nllrlhk9t6hn3UvFz0QZT60SKFY4JRARIqowlSKEVVwBqbCOgsMOcrNpwjo8y1WH7qRtL69Dfjevmbp2JXlxdTusrIFczNVyFrKw8gobtRjPSpCc6R9PARGOKXvY6bXWU8WECfhaijndNDWF0x67kGVNaKNvBIyYsy)
 
---
 
### 11. Mengelola Status Produksi/Pesanan
- [![Mengelola Status Produksi/Pesanan](https://www.plantuml.com/plantuml/png/TPDDRzim38Rl-XL4JXsmhFSUXYQEEnXBui1Mpm5Z4wbWHSeaEaN-_MXRsReYEraW7_BbbvyZO-3-P1KRjWGr_Uh9DGHps90xalKMeMRaFi8k-BRleddSKKI7JYbis0Setnq5TV2zQp5SOROYHcCXKJF02A-5QhpZu2tCT40N9T9ubqqsIs6aTAPQP3nW9CcINgDdjLHgb87vTqa6Jx0prhn1d2exK31Tp-wAIfo2w4oG_YpPQ2h-mOUMGj5-1KVla-cB4kh6Nj2Q5gE1hAvUe4K7KXU17rkRkDLIk6N-ezY2hXRRUf7fejn-TDRvEiyqZ58HNieANdUhXSwLUEStfLHoH6GmpjmjWeSH6NbCi4BBVsqZfG0-24yoIVZR-Dcdq7-uObldLIem0Vit4sM9Lm47bLHTWt83ifT1vvxI6QydSXobPGqNRzh_aXSC1Xtl_NbOU8H0Wno9a6ywYI7tgPUit6mAdMotRKUvEugAh5p6dq6m3AkxDuwgNA-NY-pdfoH7FA9LW-1m96ATBke964zdOpjPUcgVAHmmzEfPOFatVWC)](https://www.plantuml.com/plantuml/png/TPDDRzim38Rl-XL4JXsmhFSUXYQEEnXBui1Mpm5Z4wbWHSeaEaN-_MXRsReYEraW7_BbbvyZO-3-P1KRjWGr_Uh9DGHps90xalKMeMRaFi8k-BRleddSKKI7JYbis0Setnq5TV2zQp5SOROYHcCXKJF02A-5QhpZu2tCT40N9T9ubqqsIs6aTAPQP3nW9CcINgDdjLHgb87vTqa6Jx0prhn1d2exK31Tp-wAIfo2w4oG_YpPQ2h-mOUMGj5-1KVla-cB4kh6Nj2Q5gE1hAvUe4K7KXU17rkRkDLIk6N-ezY2hXRRUf7fejn-TDRvEiyqZ58HNieANdUhXSwLUEStfLHoH6GmpjmjWeSH6NbCi4BBVsqZfG0-24yoIVZR-Dcdq7-uObldLIem0Vit4sM9Lm47bLHTWt83ifT1vvxI6QydSXobPGqNRzh_aXSC1Xtl_NbOU8H0Wno9a6ywYI7tgPUit6mAdMotRKUvEugAh5p6dq6m3AkxDuwgNA-NY-pdfoH7FA9LW-1m96ATBke964zdOpjPUcgVAHmmzEfPOFatVWC)
 
---
 
### 12. Melihat Dashboard/Laporan
- [![Melihat Dashboard/Laporan](https://www.plantuml.com/plantuml/png/VPB1QiCm38RlVWhHqmOhk_SmIjCU1WqTP7i09LPR4yVEP6TRttwgdOn2M6z1_wzFlwoiGqIEGsTLDD4ILFGva6i8bb2IDMUCiCLmhZsoVjvZxncTKjX4pt3uTiIgzeFJo1TOp8mBm00VhwhnBhAtDuuYLonnycmBHKu2t49AhybcjLGQ8zOOwAhdhwnib4efOFaYWs05cw55q7z1x9XOD75i2t4Of-dduMXi97uZDZBcKOaowLzeZG0CPCiabI85j1IgeUjatP4WhMNIDw9Nk_skU0VFcZWyGO-NJjOAIiJbnBXk0cpSgSKWmMxeJ8su3wdv3ZtRnY5pT4-2HGVINICFi_Z5MUvz1vyW9yQZQUVmgLxcUf7guridHnettO99dfh_kOQOykLM4B7hZMqbz6HOIwVyaxy)](https://www.plantuml.com/plantuml/png/VPB1QiCm38RlVWhHqmOhk_SmIjCU1WqTP7i09LPR4yVEP6TRttwgdOn2M6z1_wzFlwoiGqIEGsTLDD4ILFGva6i8bb2IDMUCiCLmhZsoVjvZxncTKjX4pt3uTiIgzeFJo1TOp8mBm00VhwhnBhAtDuuYLonnycmBHKu2t49AhybcjLGQ8zOOwAhdhwnib4efOFaYWs05cw55q7z1x9XOD75i2t4Of-dduMXi97uZDZBcKOaowLzeZG0CPCiabI85j1IgeUjatP4WhMNIDw9Nk_skU0VFcZWyGO-NJjOAIiJbnBXk0cpSgSKWmMxeJ8su3wdv3ZtRnY5pT4-2HGVINICFi_Z5MUvz1vyW9yQZQUVmgLxcUf7guridHnettO99dfh_kOQOykLM4B7hZMqbz6HOIwVyaxy)
 
---
 
### 13. Mencatat Pembayaran Owner
- [![Mencatat Pembayaran Owner](https://www.plantuml.com/plantuml/png/ZL91Ri8m4Bpx5IjE804Fu5018QqYDO28EQCbNe5LnwQsqog_xvAGAaWzz1HdPtPclEjbYEXZNHaHTJG41NtMP4k26UJynOWHzbITiK6F5dRVbhmGM4Rd7pzdLrk5le7HXY9gm_I05kq8CC0n4wMpqJi38ya2WJkriqbNC-HRbam4MVPldaYvKsGwF1UAavmn4BiyJYsoMGlHne3P2vl10Z9xgoFSVYCBhZ8c4yOybSwhFJOLsutvI3vJKxXrXRlmH32nft-XqGg3XgGul4w10nEukzaKhAkqHTEpyt-9JxlkJB5BVk_RhBbldRvbMv27rRPO9JBRROTWjYtIW-n5mX0gqlSqaL0Syt4Fpx7YPSJ97xGsJvXVU2Bg55tax6Y6SuAAMAE-QeXuqLSU7C10vhZVh6JQoxIV4p-TM8TdtYFma72wwi3FfU4Tgs6oP9VdcMmh_SGV5pbfrKwstwcdS7EMbn_gZq2XNIbZtU8NqDaCxnB9dz7NOicM_BP_00)](https://www.plantuml.com/plantuml/png/ZL91Ri8m4Bpx5IjE804Fu5018QqYDO28EQCbNe5LnwQsqog_xvAGAaWzz1HdPtPclEjbYEXZNHaHTJG41NtMP4k26UJynOWHzbITiK6F5dRVbhmGM4Rd7pzdLrk5le7HXY9gm_I05kq8CC0n4wMpqJi38ya2WJkriqbNC-HRbam4MVPldaYvKsGwF1UAavmn4BiyJYsoMGlHne3P2vl10Z9xgoFSVYCBhZ8c4yOybSwhFJOLsutvI3vJKxXrXRlmH32nft-XqGg3XgGul4w10nEukzaKhAkqHTEpyt-9JxlkJB5BVk_RhBbldRvbMv27rRPO9JBRROTWjYtIW-n5mX0gqlSqaL0Syt4Fpx7YPSJ97xGsJvXVU2Bg55tax6Y6SuAAMAE-QeXuqLSU7C10vhZVh6JQoxIV4p-TM8TdtYFma72wwi3FfU4Tgs6oP9VdcMmh_SGV5pbfrKwstwcdS7EMbn_gZq2XNIbZtU8NqDaCxnB9dz7NOicM_BP_00)
 
---

### Q. Domain Class Diagram
- [Class Diagram](https://www.plantuml.com/plantuml/uml/lLTDSnit3BtdL-pufAPsFguzHR5d6iyqZYToSeUMq2uYBgcIe3rkf_-zecXnfGLPsvEfJ_RYuH5u80bGJVF1CpWEWtxLD0qJQspEDNZVN11q3ePcGPvnQ2xDohe1F6qDIqscywyYmw_9R23wjP4rPtQq38oNhJKB-WkRTz4jWSqtZwxvEtutpLaJFBfBrVosNPgnGtTeDp3W5bcmsqRQ0nlm_iuwzGbyBq1djMIGdxTCjn7uQAr6C0dvjO70FHgc5XXd-uKp_nT9wC5_tHfcCSvLpaxw_dEWzzfP5Le-1yREkljHUljWASZFM0xoH47H7iN4V6ujgJsWK4BbFCVyDiaWqyjGCRk130rX-E8KEidygTm553OA63yVH9pz6S0myVqO-X71ty4Hc0FTjyaWTMUeh1iOjwWMmCPH6zqliAK1zDxiDU8jNfV1UfbQq6tGmFWHV6B7gepydpy83mNvic6oPYoBtNsBgcGbD_SRMHIv6qTLMGJNzk2wPrK0r8_WUS6sNTTtEmicl_EStm9fM6eiKsgNDtQliGH--oKBaEmlU5FFhRRke8_4psbQ6NZ1l1QmrDR4St1GicmJ6MQqcAAnZFw54j_tvfA0zWWJ8lw_d89dE-3XFYTBSQlBexAt1g_2i4GdCMT_OAc3vwvwxUoADCwEbZujBdfQNAwcB4s6BCiw9JLbuDmg8ImX5y0HYNzkQC0ZRC70mGjUvy2e6ykWPRzfmRIeDQevYrKp2h45VaNmrkJ5HMF-FKSHdJaNDoKuCtWtINLwKbBWcJkEAPlSDP2QLHfPBlebup0fV3GzCk4N1ZQ-jvoZosbOySatl3BbWY6kGCGuNEKMKApp8YnPLBac-m8PI4_5Pq2Me3ox7Xrugw1NfFM0XYMUBt7gu5LbAQUihr2cfqdsr9bHijfzbvJ6UsxgJRZS7zBoCy4zdR2gpo-u7z0SlZUJGIQOeUALp-XdvDugeG466moFzPgmYgqYebJk154AbY67gs0ac8esW5l7IofcGVp_eHO2IokMKB7ZISSdydpq8wDFXkAkEpjKrBEj06qFfYieh1yMXwrrwdp7cnL2dkPWppv1yw28_x3Tg5RRhgIKOQdB3xIKNOa3RUprWc2r-Wuwe2oDmRiAGfkvKWwzBCwT8yQjWbcELb4iVaMUl3zfpiwQatTlthm-sQDRre03QLhJ0MVd-reufsT-v30wHOuQ1IxpieEW7_qyc4ICp-MSMjbTKHSChC4qLcCVIQaPFeVrU4LAJxgOgkc0Wulq4NWAKz46UHT_0mfY_Fn0EwQdopWfopV_NsxB09oz8bnr10QzpI66J_PnRzwFph7tRmbBTEIB-ob3P5OKIfhwQOMgbBmtEQ-C57FB4tTIekCDb_44MH5ekmPFCR0uUaLILfTFNJsGu9J42LeUkgEuJ9jGylmxSitMd9XqTxX2XyRJg-hQSYAaqzy2by-QJCcWem7U7XoxjsaQrUcrg5rOGb-bvJQUd8CclnFs0OqAW_uN)

### R. ERD

```mermaid
erDiagram
    users ||--o{ orders : creates
    users ||--o{ payments : receives_voids_refunds
    users ||--o{ order_status_history : changes
    users ||--o{ audit_log : writes

    product_categories ||--o{ products : has
    products ||--o{ product_variants : has
    product_variants ||--o{ variant_options : has
    sizes ||--o{ variant_options : defines
    colors ||--o{ variant_options : defines
    product_categories ||--o{ category_sablon_types : maps
    sablon_types ||--o{ category_sablon_types : maps

    customers ||--o{ orders : linked_to
    orders ||--o{ order_items : contains
    product_variants ||--o{ order_items : selected_variant
    sablon_types ||--o{ order_items : selected_sablon
    order_items ||--o{ order_item_details : has_details
    variant_options ||--o{ order_item_details : allocated_option
    sizes ||--o{ order_item_details : selected_size
    colors ||--o{ order_item_details : selected_color
    order_items ||--o{ order_item_designs : has_designs
    orders ||--o{ payments : has_payments
    payments ||--o{ payments : references
    orders ||--o{ order_status_history : has_history

    users {
        int user_id PK
        varchar username
        varchar password_hash
        enum role
        tinyint is_active
    }
    product_categories {
        int category_id PK
        varchar category_name
        tinyint is_active
    }
    products {
        int product_id PK
        int category_id FK
        varchar product_name
        int minimum_order
        tinyint is_active
    }
    product_variants {
        int variant_id PK
        int product_id FK
        varchar variant_name
        varchar material
        decimal price
        decimal sleeve_price
        tinyint is_active
    }
    variant_options {
        int option_id PK
        int variant_id FK
        int size_id FK
        int color_id FK
        enum sleeve_type
        int quantity
        decimal price_surcharge
        tinyint is_active
    }
    sizes {
        int size_id PK
        varchar size_name
        tinyint is_active
    }
    colors {
        int color_id PK
        varchar color_name
        tinyint is_active
    }
    sablon_types {
        int sablon_type_id PK
        varchar sablon_name
        text notes
        tinyint is_active
    }
    category_sablon_types {
        int category_sablon_id PK
        int category_id FK
        int sablon_type_id FK
        tinyint is_active
    }
    customers {
        int customer_id PK
        varchar name
        varchar phone_number
        varchar project_name
    }
    orders {
        int order_id PK
        varchar order_code
        int customer_id FK
        datetime order_date
        enum order_status
        decimal grand_total
        int user_id FK
        datetime cancelled_at
        text cancellation_reason
        int cancelled_by_user_id FK
    }
    order_items {
        int order_item_id PK
        int order_id FK
        int variant_id FK
        varchar product_name_snapshot
        varchar variant_name_snapshot
        int sablon_type_id FK
        decimal sablon_price
        decimal unit_price
        text item_notes
    }
    order_item_details {
        int order_item_detail_id PK
        int order_item_id FK
        int option_id FK
        int size_id FK
        int color_id FK
        int quantity
        enum sleeve_type
        enum fulfillment_type
        varchar custom_color
    }
    order_item_designs {
        int design_id PK
        int order_item_id FK
        varchar filename
        varchar notes
    }
    payments {
        int payment_id PK
        int order_id FK
        datetime payment_date
        enum payment_method
        decimal amount
        enum payment_status
        int received_by_user_id FK
        int voided_by_user_id FK
        int refunded_by_user_id FK
        datetime paid_at
        datetime voided_at
        datetime refunded_at
        int reference_payment_id FK
    }
    order_status_history {
        int history_id PK
        int order_id FK
        varchar from_status
        varchar to_status
        int changed_by_user_id FK
        datetime changed_at
        text notes
    }
    audit_log {
        bigint log_id PK
        varchar table_name
        int record_id
        enum action
        json old_values
        json new_values
        int user_id FK
        varchar ip_address
    }
```

### S. DFD Level 0

```mermaid
flowchart LR
    Owner[Owner]
    Kasir[Kasir]
    S((0. Sistem Informasi Siblings))

    Owner -->|1. Kredensial login owner| S
    Kasir -->|2. Kredensial login kasir| S
    S -->|3. Status autentikasi owner| Owner
    S -->|4. Status autentikasi kasir| Kasir

    Owner -->|5. Data produk, varian, opsi, tipe sablon, dan stok| S
    S -->|6. Informasi data master produk produk dan stok| Owner

    Kasir -->|7. Data item pesanan dan data order| S
    S -->|8. Nomor invoice dan ringkasan pesanan| Kasir

    Kasir -->|9. Data pembayaran kasir| S
    Owner -->|10. Data pembayaran owner| S
    S -->|11. Status pembayaran kasir| Kasir
    S -->|12. Status pembayaran owner| Owner

    Owner -->|13. Data perubahan status produksi/pesanan| S
    S -->|14. Status pesanan dan riwayat status| Owner

    Kasir -->|15. Permintaan invoice dan data pengambilan| S
    S -->|16. Invoice dan informasi pengambilan| Kasir

    Owner -->|17. Periode/filter laporan| S
    S -->|18. Dashboard dan laporan penjualan| Owner
```

### T. DFD Level 1

```mermaid
flowchart LR
    Owner[Owner]
    Kasir[Kasir]

    P1((1.0 Login))
    P2((2.0 Mengelola Data Master Produk))
    P3((3.0 Mencatat Pesanan))
    P4((4.0 Mengelola Pembayaran))
    P5((5.0 Mengelola Stok))
    P6((6.0 Mengelola Status Pesanan))
    P7((7.0 Mengelola Invoice dan Pengambilan Barang))
    P8((8.0 Menampilkan Dashboard dan Laporan Penjualan Penjualan))

    D1[(D1 users)]
    D2[(D2 product_categories, products, product_variants, variant_options)]
    D3[(D3 sizes, colors, sablon_types, category_sablon_types)]
    D4[(D4 orders, order_items, order_item_details, order_item_designs)]
    D5[(D5 payments)]
    D6[(D6 order_status_history)]

    Owner -->|1.1 Kredensial login owner| P1
    Kasir -->|1.2 Kredensial login kasir| P1
    P1 -->|1.3 Data user dan role| D1
    D1 -->|1.4 Hasil validasi user dan role| P1
    P1 -->|1.5 Status autentikasi owner| Owner
    P1 -->|1.6 Status autentikasi kasir| Kasir

    Owner -->|2.1 Data produk, varian, opsi, dan tipe sablon| P2
    D2 -->|2.2 Data Master produk| P2
    D3 -->|2.3 Data referensi ukuran, warna, dan tipe sablon| P2
    P2 -->|2.4 Perubahan data master produk produk| D2
    P2 -->|2.5 Perubahan asosiasi tipe sablon| D3
    P2 -->|2.6 Informasi data master produk tersimpan| Owner

    Kasir -->|3.1 Data item pesanan dan data order| P3
    D2 -->|3.2 Data produk aktif dan harga| P3
    D3 -->|3.3 Data ukuran, warna, dan tipe sablon aktif| P3
    P3 -->|3.4 Data pesanan baru| D4
    P3 -->|3.5 Alokasi/pengurangan stok| D2
    P3 -->|3.6 Nomor invoice dan ringkasan pesanan| Kasir

    Kasir -->|4.1 Data pembayaran dari kasir| P4
    Owner -->|4.2 Data pembayaran dari owner| P4
    D4 -->|4.3 Total tagihan pesanan| P4
    P4 -->|4.4 Data pembayaran tersimpan| D5
    P4 -->|4.5 Perubahan status pembayaran/order| D4
    P4 -->|4.6 Riwayat perubahan status pembayaran/order| D6
    P4 -->|4.7 Status pembayaran untuk kasir| Kasir
    P4 -->|4.8 Status pembayaran untuk owner| Owner

    Owner -->|5.1 Data penyesuaian stok| P5
    D2 -->|5.2 Data varian dan opsi stok| P5
    P5 -->|5.3 Data stok terbaru| D2
    P5 -->|5.4 Informasi stok| Owner

    Owner -->|6.1 Data perubahan status produksi/pesanan| P6
    D4 -->|6.2 Data pesanan| P6
    D5 -->|6.3 Data pembayaran pesanan| P6
    P6 -->|6.4 Status pesanan terbaru| D4
    P6 -->|6.5 Riwayat perubahan status| D6
    P6 -->|6.6 Status pesanan dan riwayat| Owner

    Kasir -->|7.1 Permintaan invoice dan data pengambilan| P7
    D4 -->|7.2 Data pesanan siap tampil| P7
    D5 -->|7.3 Data pembayaran pesanan| P7
    D6 -->|7.4 Status pesanan terakhir| P7
    P7 -->|7.5 Invoice dan informasi pengambilan| Kasir
    P7 -->|7.6 Data penyelesaian pengambilan| D4
    P7 -->|7.7 Riwayat penyelesaian pesanan| D6

    Owner -->|8.1 Periode/filter laporan| P8
    D4 -->|8.2 Data pesanan| P8
    D5 -->|8.3 Data pembayaran| P8
    D6 -->|8.4 Data status pesanan| P8
    P8 -->|8.5 Dashboard dan laporan penjualan| Owner
```
