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
[runnervmi13qx:39991] *** Process received signal ***
[runnervmi13qx:39991] Signal: Aborted (6)
[runnervmi13qx:39991] Signal code:  (-6)
[runnervmi13qx:39991] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fedb7645330]
[runnervmi13qx:39991] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fedb769eb2c]
[runnervmi13qx:39991] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fedb764527e]
[runnervmi13qx:39991] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fedb76288ff]
[runnervmi13qx:39991] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fedb7aa5ff5]
[runnervmi13qx:39991] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fedb7abb0da]
[runnervmi13qx:39991] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fedb7aa5a55]
[runnervmi13qx:39991] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fedb7aa5a6f]
[runnervmi13qx:39991] [ 8] plumed(+0x146dd)[0x5627a6fc06dd]
[runnervmi13qx:39991] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fedb762a1ca]
[runnervmi13qx:39991] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fedb762a28b]
[runnervmi13qx:39991] [11] plumed(+0x15365)[0x5627a6fc1365]
[runnervmi13qx:39991] *** End of error message ***
</pre>
{% endraw %}
