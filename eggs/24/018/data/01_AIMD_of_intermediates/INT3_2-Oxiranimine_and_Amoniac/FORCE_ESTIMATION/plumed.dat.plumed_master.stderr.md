**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1267-279:61500] *** Process received signal ***
[fv-az1267-279:61500] Signal: Aborted (6)
[fv-az1267-279:61500] Signal code:  (-6)
[fv-az1267-279:61500] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd0e9845330]
[fv-az1267-279:61500] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd0e989eb2c]
[fv-az1267-279:61500] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd0e984527e]
[fv-az1267-279:61500] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd0e98288ff]
[fv-az1267-279:61500] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd0e9ca5ff5]
[fv-az1267-279:61500] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd0e9cbb0da]
[fv-az1267-279:61500] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd0e9ca5a55]
[fv-az1267-279:61500] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd0e9ca5a6f]
[fv-az1267-279:61500] [ 8] plumed_master(+0x146dd)[0x5639289e26dd]
[fv-az1267-279:61500] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd0e982a1ca]
[fv-az1267-279:61500] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd0e982a28b]
[fv-az1267-279:61500] [11] plumed_master(+0x15365)[0x5639289e3365]
[fv-az1267-279:61500] *** End of error message ***
</pre>
{% endraw %}
