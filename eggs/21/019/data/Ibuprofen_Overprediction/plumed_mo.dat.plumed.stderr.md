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
[fv-az1370-99:64449] *** Process received signal ***
[fv-az1370-99:64449] Signal: Aborted (6)
[fv-az1370-99:64449] Signal code:  (-6)
[fv-az1370-99:64449] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf3a845330]
[fv-az1370-99:64449] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf3a89eb2c]
[fv-az1370-99:64449] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf3a84527e]
[fv-az1370-99:64449] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf3a8288ff]
[fv-az1370-99:64449] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf3aca5ff5]
[fv-az1370-99:64449] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf3acbb0da]
[fv-az1370-99:64449] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf3aca5a55]
[fv-az1370-99:64449] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf3aca5a6f]
[fv-az1370-99:64449] [ 8] plumed(+0x146dd)[0x5562b86ff6dd]
[fv-az1370-99:64449] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf3a82a1ca]
[fv-az1370-99:64449] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf3a82a28b]
[fv-az1370-99:64449] [11] plumed(+0x15365)[0x5562b8700365]
[fv-az1370-99:64449] *** End of error message ***
</pre>
{% endraw %}
