**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[fv-az1701-508:62288] *** Process received signal ***
[fv-az1701-508:62288] Signal: Aborted (6)
[fv-az1701-508:62288] Signal code:  (-6)
[fv-az1701-508:62288] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9f2d645330]
[fv-az1701-508:62288] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9f2d69eb2c]
[fv-az1701-508:62288] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9f2d64527e]
[fv-az1701-508:62288] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9f2d6288ff]
[fv-az1701-508:62288] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9f2daa5ff5]
[fv-az1701-508:62288] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9f2dabb0da]
[fv-az1701-508:62288] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9f2daa5a55]
[fv-az1701-508:62288] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9f2daa5a6f]
[fv-az1701-508:62288] [ 8] plumed(+0x146dd)[0x55b54c17a6dd]
[fv-az1701-508:62288] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9f2d62a1ca]
[fv-az1701-508:62288] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9f2d62a28b]
[fv-az1701-508:62288] [11] plumed(+0x15365)[0x55b54c17b365]
[fv-az1701-508:62288] *** End of error message ***
</pre>
{% endraw %}
