**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1947-163:68021] *** Process received signal ***
[fv-az1947-163:68021] Signal: Aborted (6)
[fv-az1947-163:68021] Signal code:  (-6)
[fv-az1947-163:68021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcedf845330]
[fv-az1947-163:68021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcedf89eb2c]
[fv-az1947-163:68021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcedf84527e]
[fv-az1947-163:68021] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcedf8288ff]
[fv-az1947-163:68021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcedfca5ff5]
[fv-az1947-163:68021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcedfcbb0da]
[fv-az1947-163:68021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcedfca5a55]
[fv-az1947-163:68021] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcedfca5a6f]
[fv-az1947-163:68021] [ 8] plumed_master(+0x146dd)[0x556dd69096dd]
[fv-az1947-163:68021] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcedf82a1ca]
[fv-az1947-163:68021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcedf82a28b]
[fv-az1947-163:68021] [11] plumed_master(+0x15365)[0x556dd690a365]
[fv-az1947-163:68021] *** End of error message ***
</pre>
{% endraw %}
