**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1701-508:61963] *** Process received signal ***
[fv-az1701-508:61963] Signal: Aborted (6)
[fv-az1701-508:61963] Signal code:  (-6)
[fv-az1701-508:61963] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb169245330]
[fv-az1701-508:61963] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb16929eb2c]
[fv-az1701-508:61963] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb16924527e]
[fv-az1701-508:61963] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb1692288ff]
[fv-az1701-508:61963] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb1696a5ff5]
[fv-az1701-508:61963] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb1696bb0da]
[fv-az1701-508:61963] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb1696a5a55]
[fv-az1701-508:61963] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb1696a5a6f]
[fv-az1701-508:61963] [ 8] plumed(+0x146dd)[0x55a3681c56dd]
[fv-az1701-508:61963] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb16922a1ca]
[fv-az1701-508:61963] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb16922a28b]
[fv-az1701-508:61963] [11] plumed(+0x15365)[0x55a3681c6365]
[fv-az1701-508:61963] *** End of error message ***
</pre>
{% endraw %}
