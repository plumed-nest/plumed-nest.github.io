**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1267-279:66348] *** Process received signal ***
[fv-az1267-279:66348] Signal: Aborted (6)
[fv-az1267-279:66348] Signal code:  (-6)
[fv-az1267-279:66348] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd9bca45330]
[fv-az1267-279:66348] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd9bca9eb2c]
[fv-az1267-279:66348] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd9bca4527e]
[fv-az1267-279:66348] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd9bca288ff]
[fv-az1267-279:66348] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd9bcea5ff5]
[fv-az1267-279:66348] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd9bcebb0da]
[fv-az1267-279:66348] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd9bcea5a55]
[fv-az1267-279:66348] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd9bcea5a6f]
[fv-az1267-279:66348] [ 8] plumed_master(+0x146dd)[0x55b6a6a9b6dd]
[fv-az1267-279:66348] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd9bca2a1ca]
[fv-az1267-279:66348] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd9bca2a28b]
[fv-az1267-279:66348] [11] plumed_master(+0x15365)[0x55b6a6a9c365]
[fv-az1267-279:66348] *** End of error message ***
</pre>
{% endraw %}
