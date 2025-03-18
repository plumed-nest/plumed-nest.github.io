**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[fv-az1267-279:63567] *** Process received signal ***
[fv-az1267-279:63567] Signal: Aborted (6)
[fv-az1267-279:63567] Signal code:  (-6)
[fv-az1267-279:63567] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9bfa245330]
[fv-az1267-279:63567] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9bfa29eb2c]
[fv-az1267-279:63567] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9bfa24527e]
[fv-az1267-279:63567] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9bfa2288ff]
[fv-az1267-279:63567] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9bfa6a5ff5]
[fv-az1267-279:63567] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9bfa6bb0da]
[fv-az1267-279:63567] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9bfa6a5a55]
[fv-az1267-279:63567] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9bfa6a5a6f]
[fv-az1267-279:63567] [ 8] plumed(+0x146dd)[0x55aac70376dd]
[fv-az1267-279:63567] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9bfa22a1ca]
[fv-az1267-279:63567] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9bfa22a28b]
[fv-az1267-279:63567] [11] plumed(+0x15365)[0x55aac7038365]
[fv-az1267-279:63567] *** End of error message ***
</pre>
{% endraw %}
