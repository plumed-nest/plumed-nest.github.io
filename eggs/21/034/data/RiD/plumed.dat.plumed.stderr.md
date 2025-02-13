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
[fv-az2035-366:10423] *** Process received signal ***
[fv-az2035-366:10423] Signal: Aborted (6)
[fv-az2035-366:10423] Signal code:  (-6)
[fv-az2035-366:10423] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb119045330]
[fv-az2035-366:10423] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb11909eb2c]
[fv-az2035-366:10423] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb11904527e]
[fv-az2035-366:10423] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb1190288ff]
[fv-az2035-366:10423] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb1194a5ff5]
[fv-az2035-366:10423] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb1194bb0da]
[fv-az2035-366:10423] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb1194a5a55]
[fv-az2035-366:10423] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb1194a5a6f]
[fv-az2035-366:10423] [ 8] plumed(+0x146dd)[0x55a6e78526dd]
[fv-az2035-366:10423] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb11902a1ca]
[fv-az2035-366:10423] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb11902a28b]
[fv-az2035-366:10423] [11] plumed(+0x15365)[0x55a6e7853365]
[fv-az2035-366:10423] *** End of error message ***
</pre>
{% endraw %}
