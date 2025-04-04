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
[fv-az805-507:11575] *** Process received signal ***
[fv-az805-507:11575] Signal: Aborted (6)
[fv-az805-507:11575] Signal code:  (-6)
[fv-az805-507:11575] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1f17c45330]
[fv-az805-507:11575] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1f17c9eb2c]
[fv-az805-507:11575] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1f17c4527e]
[fv-az805-507:11575] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1f17c288ff]
[fv-az805-507:11575] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1f180a5ff5]
[fv-az805-507:11575] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1f180bb0da]
[fv-az805-507:11575] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1f180a5a55]
[fv-az805-507:11575] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1f180a5a6f]
[fv-az805-507:11575] [ 8] plumed(+0x146dd)[0x55e9eaaed6dd]
[fv-az805-507:11575] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1f17c2a1ca]
[fv-az805-507:11575] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1f17c2a28b]
[fv-az805-507:11575] [11] plumed(+0x15365)[0x55e9eaaee365]
[fv-az805-507:11575] *** End of error message ***
</pre>
{% endraw %}
