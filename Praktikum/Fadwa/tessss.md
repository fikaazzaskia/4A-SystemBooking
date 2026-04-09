useCaseDiagram
    actor "Customer" as C
    actor "Mitra UMKM" as M
    actor "Admin" as A

    package "Platform Booking UMKM" {
        usecase "Login/Register" as UC1
        usecase "Cari Layanan UMKM" as UC2
        usecase "Booking Layanan" as UC3
        usecase "Kelola Jadwal & Jasa" as UC4
        usecase "Konfirmasi Pesanan" as UC5
        usecase "Validasi Mitra" as UC6
        usecase "Kelola Data User" as UC7
    }

    C --> UC1
    C --> UC2
    C --> UC3
    
    M --> UC1
    M --> UC4
    M --> UC5
    
    A --> UC1
    A --> UC6
    A --> UC7
