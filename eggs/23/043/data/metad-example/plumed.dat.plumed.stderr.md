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
[fv-az1440-40:60862] *** Process received signal ***
[fv-az1440-40:60862] Signal: Aborted (6)
[fv-az1440-40:60862] Signal code:  (-6)
[fv-az1440-40:60862] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f941ce45330]
[fv-az1440-40:60862] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f941ce9eb2c]
[fv-az1440-40:60862] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f941ce4527e]
[fv-az1440-40:60862] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f941ce288ff]
[fv-az1440-40:60862] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f941d2a5ff5]
[fv-az1440-40:60862] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f941d2bb0da]
[fv-az1440-40:60862] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f941d2a5a55]
[fv-az1440-40:60862] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f941d2a5a6f]
[fv-az1440-40:60862] [ 8] plumed(+0x146dd)[0x560c180576dd]
[fv-az1440-40:60862] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f941ce2a1ca]
[fv-az1440-40:60862] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f941ce2a28b]
[fv-az1440-40:60862] [11] plumed(+0x15365)[0x560c18058365]
[fv-az1440-40:60862] *** End of error message ***
</pre>
{% endraw %}
