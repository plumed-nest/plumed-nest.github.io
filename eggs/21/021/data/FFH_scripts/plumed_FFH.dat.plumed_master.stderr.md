**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1050-229:65181] *** Process received signal ***
[fv-az1050-229:65181] Signal: Aborted (6)
[fv-az1050-229:65181] Signal code:  (-6)
[fv-az1050-229:65181] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f5c045330]
[fv-az1050-229:65181] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f5c09eb2c]
[fv-az1050-229:65181] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f5c04527e]
[fv-az1050-229:65181] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f5c0288ff]
[fv-az1050-229:65181] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f5c4a5ff5]
[fv-az1050-229:65181] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f5c4bb0da]
[fv-az1050-229:65181] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f5c4a5a55]
[fv-az1050-229:65181] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f5c4a5a6f]
[fv-az1050-229:65181] [ 8] plumed_master(+0x146dd)[0x55b13bb0e6dd]
[fv-az1050-229:65181] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f5c02a1ca]
[fv-az1050-229:65181] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f5c02a28b]
[fv-az1050-229:65181] [11] plumed_master(+0x15365)[0x55b13bb0f365]
[fv-az1050-229:65181] *** End of error message ***
</pre>
{% endraw %}
