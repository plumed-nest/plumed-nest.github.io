**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervmeorf1:04271] *** Process received signal ***
[runnervmeorf1:04271] Signal: Aborted (6)
[runnervmeorf1:04271] Signal code:  (-6)
[runnervmeorf1:04271] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcdaee45330]
[runnervmeorf1:04271] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcdaee9eb2c]
[runnervmeorf1:04271] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcdaee4527e]
[runnervmeorf1:04271] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcdaee288ff]
[runnervmeorf1:04271] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcdaf2a5ff5]
[runnervmeorf1:04271] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcdaf2bb0da]
[runnervmeorf1:04271] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcdaf2a5a55]
[runnervmeorf1:04271] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcdaf2a5a6f]
[runnervmeorf1:04271] [ 8] plumed(+0x146dd)[0x55ffe436e6dd]
[runnervmeorf1:04271] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcdaee2a1ca]
[runnervmeorf1:04271] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcdaee2a28b]
[runnervmeorf1:04271] [11] plumed(+0x15365)[0x55ffe436f365]
[runnervmeorf1:04271] *** End of error message ***
</pre>
{% endraw %}
