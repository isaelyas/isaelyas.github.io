<!--
---Replace NO## with Number--- 
---With bash command---
---the command # Example : 
---$ i=0;for x in `cat tes.t |grep -o Clear`; do i=$((i+1));echo "$x dan $i"; sed -i "0,/Clear/s/Clear/CL-$i/g" tes.t; done # Replace string with number

---START PROCESS ---
---The command 1 (Ubah NO## ke 1..N) :	
---$ i=0;for x in `cat tes.t |grep -o "NO##"`; do i=$((i+1));echo "$x --> $i"; sed -i "0,/NO##/s/NO##/$i/g" tes.t; done # Replace string with number
---The command 2 (Ubah NO_# ke 1..N) :
---$ i=0;for x in `cat tes.t |grep -o "NO_#"`; do i=$((i+1));echo "$x --> $i"; sed -i "0,/NO_#/s/NO_#/$i/g" tes.t; done # Replace string with number
---Copy semua file yang akan ditampilkan di dir img_proc untuk diubah namanya,
---Seteleh itu copy kembali semua yang ada dalam dir img_proc ke images
---The command 3 (ubah semua nama file dalam dir img_proc menjadi picxx.jpg) : 
---$ i=0;for file in *.jpg; do i=$((i+1));echo "$i"; mv "${file}" "${file/$file/pic$i.jpg}"; done # Rename Full File Name

---Finis---
-->


<!-- ---ROW 1--- -->
		<div class="col-md-4 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
		<div class="col-md-4 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
		<div class="col-md-4 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
<!-- ---ROW 2--- -->
		<div class="col-md-6 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
		<div class="col-md-6 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
<!-- ---ROW 3--- -->
		<div class="col-md-3 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
		<div class="col-md-6 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
		<div class="col-md-3 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
<!-- ---ROW 4--- -->
		<div class="col-md-3 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
		<div class="col-md-3 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
		<div class="col-md-3 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
		<div class="col-md-3 animate-box">
			<a href="images/picNO##.jpg" class="grid-photo img-popup" style="background-image: url(images/picNO_#.jpg);">
				<div class="desc">
					<h3>View Photos</h3>
					<span>Family Photos</span>
				</div>
			</a>
		</div>
<!-- ---END_ROW--- -->


