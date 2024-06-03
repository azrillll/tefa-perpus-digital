<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">RIWAYAT KUNJUNGAN</h2>
        <div class="my-3">
          <input type="search" class="form-control form-control-lg rounded-5" placeholder="Filter...">
        </div>
        <div class="my-3 text-muted">menampilkan 1 dari 1</div>
        <table class="table">
          <thead>
            <tr>
              <td>#</td>
              <td>NAMA</td>
              <td>KEANGGOTAAN</td>
              <td>WAKTU</td>
              <td>KEPERLUAN</td>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1.</td>
              <td>azril</td>
              <td>siswa</td>
              <td>24 Februari 2024, 16.31.00</td>
              <td>Baca</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <nuxt-link to ="/">
      <button class="btn btn-primary" type="submit">kembali</button>
    </nuxt-link>
  </div>
</template>