**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[fv-az1370-99:64516] *** Process received signal ***
[fv-az1370-99:64516] Signal: Aborted (6)
[fv-az1370-99:64516] Signal code:  (-6)
[fv-az1370-99:64516] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcdd5045330]
[fv-az1370-99:64516] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcdd509eb2c]
[fv-az1370-99:64516] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcdd504527e]
[fv-az1370-99:64516] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcdd50288ff]
[fv-az1370-99:64516] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcdd54a5ff5]
[fv-az1370-99:64516] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcdd54bb0da]
[fv-az1370-99:64516] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcdd54a5a55]
[fv-az1370-99:64516] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcdd54a5a6f]
[fv-az1370-99:64516] [ 8] plumed_master(+0x146dd)[0x55e1a511f6dd]
[fv-az1370-99:64516] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcdd502a1ca]
[fv-az1370-99:64516] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcdd502a28b]
[fv-az1370-99:64516] [11] plumed_master(+0x15365)[0x55e1a5120365]
[fv-az1370-99:64516] *** End of error message ***
</pre>
{% endraw %}
