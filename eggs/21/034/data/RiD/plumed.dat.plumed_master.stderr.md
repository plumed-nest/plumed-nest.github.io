**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[fv-az1267-279:63583] *** Process received signal ***
[fv-az1267-279:63583] Signal: Aborted (6)
[fv-az1267-279:63583] Signal code:  (-6)
[fv-az1267-279:63583] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f92ade45330]
[fv-az1267-279:63583] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f92ade9eb2c]
[fv-az1267-279:63583] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f92ade4527e]
[fv-az1267-279:63583] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f92ade288ff]
[fv-az1267-279:63583] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f92ae2a5ff5]
[fv-az1267-279:63583] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f92ae2bb0da]
[fv-az1267-279:63583] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f92ae2a5a55]
[fv-az1267-279:63583] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f92ae2a5a6f]
[fv-az1267-279:63583] [ 8] plumed_master(+0x146dd)[0x55ae13a006dd]
[fv-az1267-279:63583] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f92ade2a1ca]
[fv-az1267-279:63583] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f92ade2a28b]
[fv-az1267-279:63583] [11] plumed_master(+0x15365)[0x55ae13a01365]
[fv-az1267-279:63583] *** End of error message ***
</pre>
{% endraw %}
