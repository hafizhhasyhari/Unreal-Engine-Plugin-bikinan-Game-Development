## Apaa ini tuh??

Siapa yang suka bikin game dengan Unreal Engine????
jadi program ini ya akan membantu banget sih. 
Ini adalah Plugin Unreal Engine 4 yang mengekspor data mesh navigasi ue4 (recast mesh) ke luar.

Dengan plugin ini, kamu kek bisa mengekspor data Navigasi recast langsung dari UE tanpa melalui RecastDemo. Tentu saja saya juga menyimpan navmesh recast ekspor.

### Bagaimana cara penggunaannya?

1. tambahkan plugin ke proyek dan aktifkan.
2. Luncurkan Proyek di Editor, Klik tombol `ExportNav`. Ini akan membuat file `.bin` dan `.obj`.

- File `.bin` adalah data navigasi ekspor perombakan yang langsung dari UE. Kamu dapat menggunakannya di `memutar`.
- File `.obj` adalah mesh navigasi yang diekspor dari Unreal Engine (satuannya sentimeter).

### Pakai .obj

![](https://img.imzlp.com/imgs/zlp/blog/notes/ue/index/UE4/Plugins/export-nav-data/ue4-export-nav-data-usage-0.png)

![](https://img.imzlp.com/imgs/zlp/blog/notes/ue/index/UE4/Plugins/export-nav-data/ue4-export-nav-data-usage-1.png)

3. Open The Plugin `Source/ExportNav/ThirdParty/RecastDemoBin`
4. copy `.obj` to `RecastDemoBin/Meshes`
5. run `RecastDemo.exe`

![](https://img.imzlp.com/imgs/zlp/blog/notes/ue/index/UE4/Plugins/export-nav-data/Recast-Demo-bin.png)

Credits: hafizhhasyhari

