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
[fv-az787-589:60890] *** Process received signal ***
[fv-az787-589:60890] Signal: Aborted (6)
[fv-az787-589:60890] Signal code:  (-6)
[fv-az787-589:60890] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f91e3e45330]
[fv-az787-589:60890] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f91e3e9eb2c]
[fv-az787-589:60890] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f91e3e4527e]
[fv-az787-589:60890] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f91e3e288ff]
[fv-az787-589:60890] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f91e42a5ff5]
[fv-az787-589:60890] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f91e42bb0da]
[fv-az787-589:60890] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f91e42a5a55]
[fv-az787-589:60890] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f91e42a5a6f]
[fv-az787-589:60890] [ 8] plumed(+0x146dd)[0x55854d2f96dd]
[fv-az787-589:60890] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f91e3e2a1ca]
[fv-az787-589:60890] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f91e3e2a28b]
[fv-az787-589:60890] [11] plumed(+0x15365)[0x55854d2fa365]
[fv-az787-589:60890] *** End of error message ***
</pre>
{% endraw %}
