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
[fv-az1370-99:64465] *** Process received signal ***
[fv-az1370-99:64465] Signal: Aborted (6)
[fv-az1370-99:64465] Signal code:  (-6)
[fv-az1370-99:64465] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f947d845330]
[fv-az1370-99:64465] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f947d89eb2c]
[fv-az1370-99:64465] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f947d84527e]
[fv-az1370-99:64465] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f947d8288ff]
[fv-az1370-99:64465] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f947dca5ff5]
[fv-az1370-99:64465] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f947dcbb0da]
[fv-az1370-99:64465] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f947dca5a55]
[fv-az1370-99:64465] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f947dca5a6f]
[fv-az1370-99:64465] [ 8] plumed_master(+0x146dd)[0x5604ec4316dd]
[fv-az1370-99:64465] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f947d82a1ca]
[fv-az1370-99:64465] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f947d82a28b]
[fv-az1370-99:64465] [11] plumed_master(+0x15365)[0x5604ec432365]
[fv-az1370-99:64465] *** End of error message ***
</pre>
{% endraw %}
