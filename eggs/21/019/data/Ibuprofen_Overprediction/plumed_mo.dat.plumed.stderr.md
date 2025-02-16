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
[fv-az1112-175:66879] *** Process received signal ***
[fv-az1112-175:66879] Signal: Aborted (6)
[fv-az1112-175:66879] Signal code:  (-6)
[fv-az1112-175:66879] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff612645330]
[fv-az1112-175:66879] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff61269eb2c]
[fv-az1112-175:66879] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff61264527e]
[fv-az1112-175:66879] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff6126288ff]
[fv-az1112-175:66879] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff612aa5ff5]
[fv-az1112-175:66879] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff612abb0da]
[fv-az1112-175:66879] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff612aa5a55]
[fv-az1112-175:66879] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff612aa5a6f]
[fv-az1112-175:66879] [ 8] plumed(+0x146dd)[0x55669bc2a6dd]
[fv-az1112-175:66879] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff61262a1ca]
[fv-az1112-175:66879] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff61262a28b]
[fv-az1112-175:66879] [11] plumed(+0x15365)[0x55669bc2b365]
[fv-az1112-175:66879] *** End of error message ***
</pre>
{% endraw %}
