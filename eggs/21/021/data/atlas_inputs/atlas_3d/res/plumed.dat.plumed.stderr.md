**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/res/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1701-508:64832] *** Process received signal ***
[fv-az1701-508:64832] Signal: Aborted (6)
[fv-az1701-508:64832] Signal code:  (-6)
[fv-az1701-508:64832] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9438a45330]
[fv-az1701-508:64832] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9438a9eb2c]
[fv-az1701-508:64832] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9438a4527e]
[fv-az1701-508:64832] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9438a288ff]
[fv-az1701-508:64832] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9438ea5ff5]
[fv-az1701-508:64832] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9438ebb0da]
[fv-az1701-508:64832] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9438ea5a55]
[fv-az1701-508:64832] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9438ea5a6f]
[fv-az1701-508:64832] [ 8] plumed(+0x146dd)[0x5614a3b326dd]
[fv-az1701-508:64832] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9438a2a1ca]
[fv-az1701-508:64832] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9438a2a28b]
[fv-az1701-508:64832] [11] plumed(+0x15365)[0x5614a3b33365]
[fv-az1701-508:64832] *** End of error message ***
</pre>
{% endraw %}
