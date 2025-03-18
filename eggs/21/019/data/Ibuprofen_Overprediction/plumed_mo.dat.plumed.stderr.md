**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[fv-az1983-395:64996] *** Process received signal ***
[fv-az1983-395:64996] Signal: Aborted (6)
[fv-az1983-395:64996] Signal code:  (-6)
[fv-az1983-395:64996] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f173c845330]
[fv-az1983-395:64996] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f173c89eb2c]
[fv-az1983-395:64996] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f173c84527e]
[fv-az1983-395:64996] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f173c8288ff]
[fv-az1983-395:64996] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f173cca5ff5]
[fv-az1983-395:64996] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f173ccbb0da]
[fv-az1983-395:64996] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f173cca5a55]
[fv-az1983-395:64996] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f173cca5a6f]
[fv-az1983-395:64996] [ 8] plumed(+0x146dd)[0x55fd1bd006dd]
[fv-az1983-395:64996] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f173c82a1ca]
[fv-az1983-395:64996] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f173c82a28b]
[fv-az1983-395:64996] [11] plumed(+0x15365)[0x55fd1bd01365]
[fv-az1983-395:64996] *** End of error message ***
</pre>
{% endraw %}
