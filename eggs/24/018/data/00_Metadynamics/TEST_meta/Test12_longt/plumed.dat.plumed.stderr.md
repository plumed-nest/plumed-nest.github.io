**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1701-508:61340] *** Process received signal ***
[fv-az1701-508:61340] Signal: Aborted (6)
[fv-az1701-508:61340] Signal code:  (-6)
[fv-az1701-508:61340] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcdf8045330]
[fv-az1701-508:61340] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcdf809eb2c]
[fv-az1701-508:61340] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcdf804527e]
[fv-az1701-508:61340] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcdf80288ff]
[fv-az1701-508:61340] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcdf84a5ff5]
[fv-az1701-508:61340] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcdf84bb0da]
[fv-az1701-508:61340] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcdf84a5a55]
[fv-az1701-508:61340] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcdf84a5a6f]
[fv-az1701-508:61340] [ 8] plumed(+0x146dd)[0x55d7d7add6dd]
[fv-az1701-508:61340] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcdf802a1ca]
[fv-az1701-508:61340] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcdf802a28b]
[fv-az1701-508:61340] [11] plumed(+0x15365)[0x55d7d7ade365]
[fv-az1701-508:61340] *** End of error message ***
</pre>
{% endraw %}
