**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1947-163:67691] *** Process received signal ***
[fv-az1947-163:67691] Signal: Aborted (6)
[fv-az1947-163:67691] Signal code:  (-6)
[fv-az1947-163:67691] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f19a2245330]
[fv-az1947-163:67691] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f19a229eb2c]
[fv-az1947-163:67691] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f19a224527e]
[fv-az1947-163:67691] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f19a22288ff]
[fv-az1947-163:67691] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f19a26a5ff5]
[fv-az1947-163:67691] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f19a26bb0da]
[fv-az1947-163:67691] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f19a26a5a55]
[fv-az1947-163:67691] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f19a26a5a6f]
[fv-az1947-163:67691] [ 8] plumed(+0x146dd)[0x55bf02a466dd]
[fv-az1947-163:67691] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f19a222a1ca]
[fv-az1947-163:67691] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f19a222a28b]
[fv-az1947-163:67691] [11] plumed(+0x15365)[0x55bf02a47365]
[fv-az1947-163:67691] *** End of error message ***
</pre>
{% endraw %}
