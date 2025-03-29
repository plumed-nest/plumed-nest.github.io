**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/tetra_pept/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1701-508:65091] *** Process received signal ***
[fv-az1701-508:65091] Signal: Aborted (6)
[fv-az1701-508:65091] Signal code:  (-6)
[fv-az1701-508:65091] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2d58245330]
[fv-az1701-508:65091] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2d5829eb2c]
[fv-az1701-508:65091] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2d5824527e]
[fv-az1701-508:65091] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2d582288ff]
[fv-az1701-508:65091] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2d586a5ff5]
[fv-az1701-508:65091] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2d586bb0da]
[fv-az1701-508:65091] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2d586a5a55]
[fv-az1701-508:65091] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2d586a5a6f]
[fv-az1701-508:65091] [ 8] plumed(+0x146dd)[0x5639b11816dd]
[fv-az1701-508:65091] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2d5822a1ca]
[fv-az1701-508:65091] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2d5822a28b]
[fv-az1701-508:65091] [11] plumed(+0x15365)[0x5639b1182365]
[fv-az1701-508:65091] *** End of error message ***
</pre>
{% endraw %}
