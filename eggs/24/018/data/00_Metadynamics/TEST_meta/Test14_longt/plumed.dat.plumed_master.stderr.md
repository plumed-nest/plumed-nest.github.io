**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az787-589:61009] *** Process received signal ***
[fv-az787-589:61009] Signal: Aborted (6)
[fv-az787-589:61009] Signal code:  (-6)
[fv-az787-589:61009] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9d21845330]
[fv-az787-589:61009] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9d2189eb2c]
[fv-az787-589:61009] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9d2184527e]
[fv-az787-589:61009] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9d218288ff]
[fv-az787-589:61009] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9d21ca5ff5]
[fv-az787-589:61009] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9d21cbb0da]
[fv-az787-589:61009] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9d21ca5a55]
[fv-az787-589:61009] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9d21ca5a6f]
[fv-az787-589:61009] [ 8] plumed_master(+0x146dd)[0x5602d45db6dd]
[fv-az787-589:61009] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9d2182a1ca]
[fv-az787-589:61009] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9d2182a28b]
[fv-az787-589:61009] [11] plumed_master(+0x15365)[0x5602d45dc365]
[fv-az787-589:61009] *** End of error message ***
</pre>
{% endraw %}
