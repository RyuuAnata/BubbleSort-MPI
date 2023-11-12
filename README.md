# BubbleSort-MPI

<p>
<p>Anata Ryu Ilhami (09011382126168)</p>
<p>Agung Rizqi Ramadhan (09011382126157)</p>
<p>Nanda Apriadi (09011382126170)</p>
</p>
program ini memerlukan 1 komputer yang bertindak sebagai master dan beberapa komputer lain yang bertindak sebagai slave
<p><b>UNTUK SLAVE</b>
<p>pastikan sudah menginstal NFS Client dan sudah melakukan mounting dengan perintah
<p><b>sudo mount serverhost:/lokasi/shared/folder/server /lokasi/shared/folder/client</b> </p>
<p>
<p>untuk menjalankan program masukan perintah ini di <b>MASTER</b></p>
<p><b>mpirun -np "jumlah prosesor" -host "daftar host" python3 Bubblesort.py</b></p>
