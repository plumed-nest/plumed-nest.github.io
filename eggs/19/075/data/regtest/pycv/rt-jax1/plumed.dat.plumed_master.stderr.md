**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1267-279:66245] *** Process received signal ***
[fv-az1267-279:66245] Signal: Aborted (6)
[fv-az1267-279:66245] Signal code:  (-6)
[fv-az1267-279:66245] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f05da245330]
[fv-az1267-279:66245] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f05da29eb2c]
[fv-az1267-279:66245] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f05da24527e]
[fv-az1267-279:66245] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05da2288ff]
[fv-az1267-279:66245] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f05da6a5ff5]
[fv-az1267-279:66245] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f05da6bb0da]
[fv-az1267-279:66245] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f05da6a5a55]
[fv-az1267-279:66245] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f05da6a5a6f]
[fv-az1267-279:66245] [ 8] plumed_master(+0x146dd)[0x5579fcc216dd]
[fv-az1267-279:66245] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f05da22a1ca]
[fv-az1267-279:66245] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f05da22a28b]
[fv-az1267-279:66245] [11] plumed_master(+0x15365)[0x5579fcc22365]
[fv-az1267-279:66245] *** End of error message ***
</pre>
{% endraw %}
