
# 📊 Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Jaya Jaya Maju

## 🧠 Business Understanding

**Jaya Jaya Maju** adalah perusahaan multinasional yang memiliki lebih dari 1.000 karyawan di seluruh Indonesia. Dalam beberapa tahun terakhir, perusahaan menghadapi tantangan besar terkait retensi karyawan. Tingginya angka attrition (karyawan keluar) memicu kebutuhan untuk menganalisis dan memahami faktor-faktor penyebabnya.

### 🎯 Permasalahan Bisnis

- Tingginya angka karyawan keluar (attrition) sebanyak **179 orang dari total 1.470 karyawan**.
- Kurangnya pemahaman terkait alasan utama karyawan meninggalkan perusahaan.
- Tidak tersedianya sistem monitoring SDM yang informatif dan interaktif untuk manajemen.

### 🔍 Cakupan Proyek

- Menganalisis data HR yang tersedia untuk menemukan pola-pola attrition.
- Membuat dashboard interaktif menggunakan Metabase untuk monitoring attrition.
- Memberikan insight dan rekomendasi actionable untuk pengambilan keputusan manajerial.

### ⚙️ Persiapan

**Sumber Data**: Dataset internal HR dalam format CSV  
**Kolom penting**:  
`EmployeeId`, `Attrition`, `Age`, `Gender`, `OverTime`, `Department`, `JobRole`, `MonthlyIncome`, `YearsAtCompany`, dll.

**Environment Setup**:

```bash
# Menjalankan Metabase menggunakan Docker
docker run -d -p 3000:3000 --name metabase metabase/metabase
```

---

## 📈 Business Dashboard

Dashboard dibuat menggunakan **Metabase** dan menyajikan berbagai metrik utama terkait SDM dan attrition.

**Metrik Utama**:
- 👥 Jumlah Karyawan: **1.470**
- 👋 Karyawan Keluar: **179**
- ⏳ Rata-rata Lama Bekerja: **7.01 Tahun**
- 😊 Rata-rata Kepuasan Kerja: **2.73 / 4**
- ⚖️ Rata-rata Work Life Balance: **2.76 / 4**

**Visualisasi Kunci**:
- Distribusi attrition berdasarkan **usia**, **jenis kelamin**, **status pernikahan**, dan **lembur**.
- **Departemen** dengan attrition tertinggi: Research & Development dan Sales.
- **Hubungan antara kenaikan gaji dan attrition**: semakin kecil persentase kenaikan gaji, semakin tinggi attrition.
- Jumlah karyawan berdasarkan **jabatan/posisi kerja**.

> 📎 **Link Dashboard** (Metabase Public Share - local):
> `http://localhost:3000/public/dashboard/c7e79f39-68c1-453f-9faf-aad4518daa7a`

---

## ✅ Conclusion

- Karyawan yang bekerja **lembur** memiliki risiko lebih tinggi untuk keluar (**54.7%** dari total attrition).
- Rentang usia **25–35 tahun** paling rentan keluar.
- Karyawan dengan status **single** lebih banyak meninggalkan perusahaan.
- Departemen **Research & Development** menyumbang jumlah attrition tertinggi.
- Karyawan dengan **kenaikan gaji rendah (<15%)** lebih sering keluar dari perusahaan.

---

## 🚀 Rekomendasi Action Items

- 🔁 **Evaluasi ulang kebijakan lembur** dan dorong keseimbangan kerja-hidup.
- 💰 **Tinjau kembali skema kompensasi dan kenaikan gaji** secara lebih kompetitif.
- 📚 **Tingkatkan retensi karyawan muda** melalui mentoring dan peluang pengembangan karir.
- 📋 **Lakukan survei internal berkala** untuk memahami kondisi karyawan secara lebih mendalam.

---
