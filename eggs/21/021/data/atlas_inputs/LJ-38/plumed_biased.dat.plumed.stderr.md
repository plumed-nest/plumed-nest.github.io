**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/LJ-38/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1701-508:64577] *** Process received signal ***
[fv-az1701-508:64577] Signal: Aborted (6)
[fv-az1701-508:64577] Signal code:  (-6)
[fv-az1701-508:64577] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fba38c45330]
[fv-az1701-508:64577] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fba38c9eb2c]
[fv-az1701-508:64577] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fba38c4527e]
[fv-az1701-508:64577] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fba38c288ff]
[fv-az1701-508:64577] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fba390a5ff5]
[fv-az1701-508:64577] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fba390bb0da]
[fv-az1701-508:64577] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fba390a5a55]
[fv-az1701-508:64577] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fba390a5a6f]
[fv-az1701-508:64577] [ 8] plumed(+0x146dd)[0x55e07c0956dd]
[fv-az1701-508:64577] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fba38c2a1ca]
[fv-az1701-508:64577] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fba38c2a28b]
[fv-az1701-508:64577] [11] plumed(+0x15365)[0x55e07c096365]
[fv-az1701-508:64577] *** End of error message ***
</pre>
{% endraw %}
