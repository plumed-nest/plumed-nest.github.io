**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[fv-az805-507:11591] *** Process received signal ***
[fv-az805-507:11591] Signal: Aborted (6)
[fv-az805-507:11591] Signal code:  (-6)
[fv-az805-507:11591] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f945d245330]
[fv-az805-507:11591] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f945d29eb2c]
[fv-az805-507:11591] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f945d24527e]
[fv-az805-507:11591] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f945d2288ff]
[fv-az805-507:11591] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f945d6a5ff5]
[fv-az805-507:11591] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f945d6bb0da]
[fv-az805-507:11591] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f945d6a5a55]
[fv-az805-507:11591] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f945d6a5a6f]
[fv-az805-507:11591] [ 8] plumed_master(+0x146dd)[0x55e81d76d6dd]
[fv-az805-507:11591] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f945d22a1ca]
[fv-az805-507:11591] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f945d22a28b]
[fv-az805-507:11591] [11] plumed_master(+0x15365)[0x55e81d76e365]
[fv-az805-507:11591] *** End of error message ***
</pre>
{% endraw %}
