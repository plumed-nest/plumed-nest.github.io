**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1267-279:61553] *** Process received signal ***
[fv-az1267-279:61553] Signal: Aborted (6)
[fv-az1267-279:61553] Signal code:  (-6)
[fv-az1267-279:61553] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f24e0245330]
[fv-az1267-279:61553] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f24e029eb2c]
[fv-az1267-279:61553] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f24e024527e]
[fv-az1267-279:61553] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24e02288ff]
[fv-az1267-279:61553] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24e06a5ff5]
[fv-az1267-279:61553] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24e06bb0da]
[fv-az1267-279:61553] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24e06a5a55]
[fv-az1267-279:61553] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24e06a5a6f]
[fv-az1267-279:61553] [ 8] plumed_master(+0x146dd)[0x5584d2bfe6dd]
[fv-az1267-279:61553] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f24e022a1ca]
[fv-az1267-279:61553] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f24e022a28b]
[fv-az1267-279:61553] [11] plumed_master(+0x15365)[0x5584d2bff365]
[fv-az1267-279:61553] *** End of error message ***
</pre>
{% endraw %}
