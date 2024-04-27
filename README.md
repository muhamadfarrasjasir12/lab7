# lab7

CREATE TABLE `berita` (

  `id_berita` int(11) NOT NULL,
  
  `judul` varchar(100) NOT NULL,
  
  `id_kategori` int(11) NOT NULL,
  
  `gambar` varchar(100) NOT NULL,
  
  `teks_berita` text NOT NULL,
  
  `tgl_posting` datetime NOT NULL,
  
  `id_admin` int(11) NOT NULL,
  
  `dilihat` int(11) NOT NULL
  
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

