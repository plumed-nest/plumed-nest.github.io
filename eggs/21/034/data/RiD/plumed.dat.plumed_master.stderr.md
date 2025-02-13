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
[fv-az2035-366:10439] *** Process received signal ***
[fv-az2035-366:10439] Signal: Aborted (6)
[fv-az2035-366:10439] Signal code:  (-6)
[fv-az2035-366:10439] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe9b5045330]
[fv-az2035-366:10439] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe9b509eb2c]
[fv-az2035-366:10439] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe9b504527e]
[fv-az2035-366:10439] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe9b50288ff]
[fv-az2035-366:10439] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe9b54a5ff5]
[fv-az2035-366:10439] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe9b54bb0da]
[fv-az2035-366:10439] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe9b54a5a55]
[fv-az2035-366:10439] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe9b54a5a6f]
[fv-az2035-366:10439] [ 8] plumed_master(+0x146dd)[0x559db93e76dd]
[fv-az2035-366:10439] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe9b502a1ca]
[fv-az2035-366:10439] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe9b502a28b]
[fv-az2035-366:10439] [11] plumed_master(+0x15365)[0x559db93e8365]
[fv-az2035-366:10439] *** End of error message ***
</pre>
{% endraw %}
