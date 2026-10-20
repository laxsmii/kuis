<?php
function hitungNilaiAkhir($tugas, $uts, $uas) {
    return ($tugas * 0.30) + ($uts * 0.30) + ($uas * 0.40);
}

function tentukanStatus($nilai) {
    return ($nilai >= 70) ? "Lulus" : "Tidak Lulus";
}

// Nilai masukan
$tugas = 80;
$uts   = 80;
$uas   = 87.5;

$nilaiAkhir = hitungNilaiAkhir($tugas, $uts, $uas);
$status     = tentukanStatus($nilaiAkhir);

echo "<h3>Hasil Program Biasa</h3>";
echo "Nilai Tugas: $tugas<br>";
echo "Nilai UTS: $uts<br>";
echo "Nilai UAS: $uas<br>";
echo "Nilai Akhir: " . round($nilaiAkhir) . "<br>";
echo "Status: $status";
?>
