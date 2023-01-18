c = Canvas(root, width=canvas_width, height=canvas_height, background="deep skyblue") =>> untuk menampilkan warna background, lebar, dan tinggi pada game telur
color_cycle = cycle(["light blue", "light green", "light pink", "light yellow", "light cyan"]) =>> untuk memberikan warna-warna telur agar tampak bewarna
difficulty = 0.95 =>> digunakan untuk kecepatan bergerak telur 
catcher_color = "blue" =>>  digunakan untuk memberikan warna garis pada penangkap telur
egg_width = 45 =>> digunakan untuk lebarnya telur
egg_height = 55 =>> digunakan untuk tingginya telur
def egg_dropped(egg): =>> untuk menampilkan kalah atau menangnya game telur berjatuhan
def move_eggs(): =>> untuk memindahkan telur 
def create_egg(): =>> digunakan untuk membuat telur serta isi ukurannya
def lose_a_life(): =>> digunakan untuk menampilkan kehilangan nyawa telur atau kehilangan kesempatan
def check_catch(): =>> untuk mengetahui cek tangkap telur
def increase_score(points): =>> digunakan untuk meningkatkan point atau skor pada game telur
def move_left(event): =>> digunakan untuk menggerakkan penangkap atau keranjang telur ke kiri
def move_right(event): =>> digunakan untuk menggerakkan penangkap atau keranjang telur ke kanan
text="Nilai: "+ str(score)) =>> digunakan untuk menampilkan skor atau nilai
