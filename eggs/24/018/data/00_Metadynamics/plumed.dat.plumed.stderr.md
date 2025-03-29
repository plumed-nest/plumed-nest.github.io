**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1701-508:61548] *** Process received signal ***
[fv-az1701-508:61548] Signal: Aborted (6)
[fv-az1701-508:61548] Signal code:  (-6)
[fv-az1701-508:61548] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc4e445330]
[fv-az1701-508:61548] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc4e49eb2c]
[fv-az1701-508:61548] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc4e44527e]
[fv-az1701-508:61548] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc4e4288ff]
[fv-az1701-508:61548] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc4e8a5ff5]
[fv-az1701-508:61548] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc4e8bb0da]
[fv-az1701-508:61548] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc4e8a5a55]
[fv-az1701-508:61548] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc4e8a5a6f]
[fv-az1701-508:61548] [ 8] plumed(+0x146dd)[0x55ad8bff26dd]
[fv-az1701-508:61548] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc4e42a1ca]
[fv-az1701-508:61548] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc4e42a28b]
[fv-az1701-508:61548] [11] plumed(+0x15365)[0x55ad8bff3365]
[fv-az1701-508:61548] *** End of error message ***
</pre>
{% endraw %}
