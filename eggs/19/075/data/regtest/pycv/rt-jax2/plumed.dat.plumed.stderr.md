**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1665-105:14984] *** Process received signal ***
[fv-az1665-105:14984] Signal: Aborted (6)
[fv-az1665-105:14984] Signal code:  (-6)
[fv-az1665-105:14984] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0186c45330]
[fv-az1665-105:14984] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0186c9eb2c]
[fv-az1665-105:14984] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0186c4527e]
[fv-az1665-105:14984] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0186c288ff]
[fv-az1665-105:14984] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f01870a5ff5]
[fv-az1665-105:14984] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f01870bb0da]
[fv-az1665-105:14984] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f01870a5a55]
[fv-az1665-105:14984] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f01870a5a6f]
[fv-az1665-105:14984] [ 8] plumed(+0x146dd)[0x56417647a6dd]
[fv-az1665-105:14984] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0186c2a1ca]
[fv-az1665-105:14984] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0186c2a28b]
[fv-az1665-105:14984] [11] plumed(+0x15365)[0x56417647b365]
[fv-az1665-105:14984] *** End of error message ***
</pre>
{% endraw %}
