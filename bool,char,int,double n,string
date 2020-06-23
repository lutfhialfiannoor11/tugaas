#include <iostream>
#include <string>
#include <windows.h>

using namespace std;

string nama, prodi, nim;
char pilihan;
int angkatan;
float nilai;
bool hasil, hasil2;
double a, b, c, d, e, f, g, h, i, j, k, l, m, n, o, p;


void program(){
	
	system("cls");

	cout << "\nMasukan Prodi  [Inisial]\t>> "	; cin >> prodi;
	cout << "\nMasukan Angkatan [Tahun]\t>> "	; cin >> angkatan;
	cout << "\nMasukan NIM\t\t\t>> "			; cin >> nim;
	
	system("cls");
	
	cout << "\nmasukan Nilai Bahasa Pemrograman"				<< "\t\t\t>> "	; cin >> a;
	cout << "\nmasukan Nilai Elektronika Terintegrasi"			<< "\t\t\t>> "	; cin >> b;
	cout << "\nmasukan Nilai Fisika Lanjut"						<< "\t\t\t\t>> "; cin >> c;
	cout << "\nmasukan Nilai Ilmu Kesehatan Masyarakat"			<< "\t\t\t>> "	; cin >> d;
	cout << "\nmasukan Nilai Instalasi Listrik"					<< "\t\t\t\t>> "; cin >> e;
	cout << "\nmasukan Nilai Kewarganegaraan"					<< "\t\t\t\t>> "; cin >> f;
	cout << "\nmasukan Nilai Kewirausahaan"						<< "\t\t\t\t>> "; cin >> g;
	cout << "\nmasukan Nilai Sensor dan Tranduser"				<< "\t\t\t>> "	; cin >> h;
	cout << "\nmasukan Nilai Teknik Digital"					<< "\t\t\t\t>> "; cin >> i;
	cout << "\nmasukan Nilai Teknik Tenaga Listrik"				<< "\t\t\t>> "	; cin >> j;
	cout << "\nmasukan Nilai Praktikum Bahasa Pemrograman"		<< "\t\t>> "	; cin >> k;
	cout << "\nmasukan Nilai Praktikum Elektronika Terintegrasi"<< "\t>> "		; cin >> l;
	cout << "\nmasukan Nilai Praktikum Fisika Lanjut"			<< "\t\t\t>> "	; cin >> m;
	cout << "\nmasukan Nilai Praktikum Instalasi Listrik"		<< "\t\t>> "	; cin >> n;
	cout << "\nmasukan Nilai Praktikum Teknik Digital"			<< "\t\t\t>> "	; cin >> o;
	cout << "\nmasukan Nilai Praktikum Teknik Tenaga Listrik"	<< "\t\t>> "	; cin >> p;
	
	nilai = ((a + b + c + d + e + f + g + h + i + j + k + l + m + n +  o + p) / 16);
	
	hasil2 = nilai <= 70.09;
	hasil = nilai >= 70.09;
	
	cout << "\n\n-NAMA\t: " << nama;
	cout << "\t-NIM\t: " << nim;
	cout << "\t-PRODI\t: " << prodi;
	cout << "\t-ANGKATAN\t: " << angkatan << "\n\n";
	
	
	
	if (nilai <= 40.09){
		cout << "Anda Mendapatkan Predikat E dengan Nilai\t: "	<< nilai << "\n";
	}else if (nilai <= 54.09){
		cout << "Anda Mendapatkan Predikat D dengan Nilai\t: "	<< nilai << "\n";
	}else if (nilai <= 60.09){
		cout << "Anda Mendapatkan Predikat C dengan Nilai\t: "	<< nilai << "\n";
	}else if (nilai <= 70.09){
		cout << "Anda Mendapatkan Predikat BC dengan Nilai\t: "	<< nilai << "\n";
	}else if (nilai <= 80.09){
		cout << "Anda Mendapatkan Predikat B dengan Nilai\t: "	<< nilai << "\n";
	}else if (nilai <= 85.09){
		cout << "Anda Mendapatkan Predikat AB dengan Nilai\t: "	<< nilai << "\n";
	}else if (nilai <= 100){
		cout << "Anda Mendapatkan Predikat A dengan Nilai\t: "	<< nilai << "\n";
	}else{
		cout << "pilihan anda tidak valid!\n";
	}
	
	if (hasil){
		cout << "\nAnda Lulus\n";
	}
	else if (hasil2){
		cout << "\nAnda Tidak Lulus\n";
	}
}

int main(){
	
	cout << "Selamat Datang, Siapa Nama Anda ?\t>> "; getline (cin, nama);
	system("cls");
	
	awal :
		cout << "Halo, ' " << nama << " ' Apakah anda ingin memeriksa nilai ? [Y / N]\t>> "; cin >> pilihan;
	
	while(true){
		
		if (pilihan == 'y' || pilihan == 'Y'){
			program();
			break;
		}
		else if (pilihan == 'n' || pilihan == 'N'){
			cout << "\nTerima Kasih Atas Kunjungannya...";
			break;
		}
		else{
			cout << "\nPilihan Anda Tidak Valid!\n"; goto awal;
		}
	}
	
	return 0;
}
