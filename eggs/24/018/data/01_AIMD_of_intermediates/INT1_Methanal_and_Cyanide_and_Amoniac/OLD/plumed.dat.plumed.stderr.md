**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/OLD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1267-279:61122] *** Process received signal ***
[fv-az1267-279:61122] Signal: Aborted (6)
[fv-az1267-279:61122] Signal code:  (-6)
[fv-az1267-279:61122] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd4d0445330]
[fv-az1267-279:61122] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd4d049eb2c]
[fv-az1267-279:61122] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd4d044527e]
[fv-az1267-279:61122] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4d04288ff]
[fv-az1267-279:61122] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4d08a5ff5]
[fv-az1267-279:61122] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4d08bb0da]
[fv-az1267-279:61122] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4d08a5a55]
[fv-az1267-279:61122] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4d08a5a6f]
[fv-az1267-279:61122] [ 8] plumed(+0x146dd)[0x557ff7eb96dd]
[fv-az1267-279:61122] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd4d042a1ca]
[fv-az1267-279:61122] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd4d042a28b]
[fv-az1267-279:61122] [11] plumed(+0x15365)[0x557ff7eba365]
[fv-az1267-279:61122] *** End of error message ***
</pre>
{% endraw %}
