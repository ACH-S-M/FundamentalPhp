<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Form Parkir Kendaraan</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gradient-to-br from-cyan-100 to-blue-100 min-h-screen flex items-center justify-center">
  <form class="bg-white p-6 rounded-xl shadow-lg w-full max-w-md space-y-4">
    <h2 class="text-2xl font-bold text-center text-gray-800">Form Parkir Kendaraan</h2>

    <div>
      <label class="block mb-1 text-sm font-medium text-gray-700">Plat Nomor Kendaraan</label>
      <input type="text" class="w-full border rounded-md p-2 focus:outline-none focus:ring-2 focus:ring-cyan-500" placeholder="B 1234 XYZ">
    </div>

    <div>
      <label class="block mb-1 text-sm font-medium text-gray-700">Jenis Kendaraan</label>
      <select class="w-full border rounded-md p-2 bg-white focus:outline-none focus:ring-2 focus:ring-cyan-500">
        <option>Pilih</option>
        <option>Motor</option>
        <option>Mobil</option>
        <option>Truk</option>
      </select>
    </div>

    <div>
      <label class="block mb-1 text-sm font-medium text-gray-700">Waktu Masuk</label>
      <input type="datetime-local" class="w-full border rounded-md p-2 focus:outline-none focus:ring-2 focus:ring-cyan-500">
    </div>

    <div>
      <label class="block mb-1 text-sm font-medium text-gray-700">Waktu Keluar</label>
      <input type="datetime-local" class="w-full border rounded-md p-2 focus:outline-none focus:ring-2 focus:ring-cyan-500">
    </div>

    <div>
      <label class="block mb-1 text-sm font-medium text-gray-700">Uang Bayar (Rp)</label>
      <input type="number" class="w-full border rounded-md p-2 focus:outline-none focus:ring-2 focus:ring-cyan-500" placeholder="Contoh: 10000">
    </div>

    <div class="text-sm font-semibold text-gray-700">
      <p>Total Bayar: <span class="font-normal text-black">-</span></p>
      <p>Kembalian: <span class="font-normal text-black">-</span></p>
    </div>

    <button type="submit" class="w-full bg-cyan-700 hover:bg-cyan-800 text-white font-semibold py-2 rounded-lg transition">Bayar</button>
  </form>
</body>
</html>
