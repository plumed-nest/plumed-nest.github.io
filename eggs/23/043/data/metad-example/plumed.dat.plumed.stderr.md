**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[fv-az1267-279:61592] *** Process received signal ***
[fv-az1267-279:61592] Signal: Aborted (6)
[fv-az1267-279:61592] Signal code:  (-6)
[fv-az1267-279:61592] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f27e9445330]
[fv-az1267-279:61592] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f27e949eb2c]
[fv-az1267-279:61592] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f27e944527e]
[fv-az1267-279:61592] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f27e94288ff]
[fv-az1267-279:61592] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f27e98a5ff5]
[fv-az1267-279:61592] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f27e98bb0da]
[fv-az1267-279:61592] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f27e98a5a55]
[fv-az1267-279:61592] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f27e98a5a6f]
[fv-az1267-279:61592] [ 8] plumed(+0x146dd)[0x55e338c2d6dd]
[fv-az1267-279:61592] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f27e942a1ca]
[fv-az1267-279:61592] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f27e942a28b]
[fv-az1267-279:61592] [11] plumed(+0x15365)[0x55e338c2e365]
[fv-az1267-279:61592] *** End of error message ***
</pre>
{% endraw %}
