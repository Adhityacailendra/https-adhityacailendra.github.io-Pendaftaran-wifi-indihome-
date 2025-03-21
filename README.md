# Pendaftaran-wifi-indihome
Formulir pendaftaran dan verifikasi pelanggan untuk layanan internet indihome di wilayah baturaja dan sekitarnya. mohon hubungi 082281512603 untuk konfirmasi pemasangan
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kirim Link Registrasi Customer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
</head>
<body class="bg-gray-100 flex flex-col items-center justify-center min-h-screen">
    <div class="w-full max-w-md mx-auto bg-white rounded-lg shadow-md p-6">
        <div class="flex items-center mb-6">
            <i class="fas fa-arrow-left text-xl text-gray-700 cursor-pointer" onclick="goBack()"></i>
            <h1 class="text-xl font-bold text-center flex-grow text-gray-900">Kirim Link Registrasi Customer</h1>
        </div>
        <form id="registrationForm">
            <div class="mb-4">
                <label class="block text-gray-700 text-sm font-bold mb-2" for="nama-pelanggan">Nama Pelanggan</label>
                <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="nama-pelanggan" type="text" placeholder="Nama lengkap pelanggan" required/>
            </div>
            <div class="mb-4">
                <label class="block text-gray-700 text-sm font-bold mb-2" for="email-pelanggan">Email Pelanggan</label>
                <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="email-pelanggan" type="email" placeholder="Alamat email pelanggan" required/>
            </div>
            <div class="mb-6">
                <label class="block text-gray-700 text-sm font-bold mb-2" for="no-handphone">No. Handphone</label>
                <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="no-handphone" type="tel" placeholder="No. handphone pelanggan" required/>
            </div>
            <div class="flex items-center justify-center">
                <button class="bg-red-400 hover:bg-red-500 text-white font-bold py-2 px-4 rounded-full focus:outline-none focus:shadow-outline" type="submit">