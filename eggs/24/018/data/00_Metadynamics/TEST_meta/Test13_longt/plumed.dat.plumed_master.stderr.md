**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az787-589:60958] *** Process received signal ***
[fv-az787-589:60958] Signal: Aborted (6)
[fv-az787-589:60958] Signal code:  (-6)
[fv-az787-589:60958] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad37245330]
[fv-az787-589:60958] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad3729eb2c]
[fv-az787-589:60958] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad3724527e]
[fv-az787-589:60958] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad372288ff]
[fv-az787-589:60958] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad376a5ff5]
[fv-az787-589:60958] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad376bb0da]
[fv-az787-589:60958] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad376a5a55]
[fv-az787-589:60958] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad376a5a6f]
[fv-az787-589:60958] [ 8] plumed_master(+0x146dd)[0x55681df2a6dd]
[fv-az787-589:60958] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad3722a1ca]
[fv-az787-589:60958] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad3722a28b]
[fv-az787-589:60958] [11] plumed_master(+0x15365)[0x55681df2b365]
[fv-az787-589:60958] *** End of error message ***
</pre>
{% endraw %}
