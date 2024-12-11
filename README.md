# LABPY.08
# NAMA: AGUNG HERLAMBANG 
# NIM: 312410296
# MATKUL: BAHASA PEMROGRAMAN

# PRATIKUM
<img width="576" alt="Screenshot 2024-12-11 194428" src="https://github.com/user-attachments/assets/ef7345a9-e70a-4076-829b-8fba49715fd3">

# LABPY.08
class Mahasiswa: def init(self, nama, nilai): self.nama = nama self.nilai = nilai

class DaftarNilaiMahasiswa: def init(self): self.daftar_nilai = {}

```pyhton
def tambah(self, nama, nilai):
    """Menambahkan data mahasiswa"""
    self.daftar_nilai[nama] = Mahasiswa(nama, nilai)
    print(f"Data {nama} berhasil ditambahkan.")

def tampilkan(self):
    """Menampilkan data mahasiswa"""
    print("Daftar Nilai Mahasiswa:")
    for mahasiswa in self.daftar_nilai.values():
        print(f"Nama: {mahasiswa.nama}, Nilai: {mahasiswa.nilai}")

def hapus(self, nama):
    """Menghapus data mahasiswa berdasarkan nama"""
    if nama in self.daftar_nilai:
        del self.daftar_nilai[nama]
        print(f"Data {nama} berhasil dihapus.")
    else:
        print(f"Data {nama} tidak ditemukan.")

def ubah(self, nama, nilai_baru):
    """Mengubah data mahasiswa berdasarkan nama"""
    if nama in self.daftar_nilai:
        self.daftar_nilai[nama].nilai = nilai_baru
        print(f"Data {nama} berhasil diubah.")
    else:
        print(f"Data {nama} tidak ditemukan.")
