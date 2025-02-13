**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az1665-105:14847] *** Process received signal ***
[fv-az1665-105:14847] Signal: Aborted (6)
[fv-az1665-105:14847] Signal code:  (-6)
[fv-az1665-105:14847] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efcc0e45330]
[fv-az1665-105:14847] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efcc0e9eb2c]
[fv-az1665-105:14847] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efcc0e4527e]
[fv-az1665-105:14847] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efcc0e288ff]
[fv-az1665-105:14847] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efcc12a5ff5]
[fv-az1665-105:14847] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efcc12bb0da]
[fv-az1665-105:14847] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efcc12a5a55]
[fv-az1665-105:14847] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efcc12a5a6f]
[fv-az1665-105:14847] [ 8] plumed_master(+0x146dd)[0x557d548e46dd]
[fv-az1665-105:14847] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efcc0e2a1ca]
[fv-az1665-105:14847] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efcc0e2a28b]
[fv-az1665-105:14847] [11] plumed_master(+0x15365)[0x557d548e5365]
[fv-az1665-105:14847] *** End of error message ***
</pre>
{% endraw %}
