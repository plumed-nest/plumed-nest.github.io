**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[fv-az1047-397:67196] *** Process received signal ***
[fv-az1047-397:67196] Signal: Aborted (6)
[fv-az1047-397:67196] Signal code:  (-6)
[fv-az1047-397:67196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0312a45330]
[fv-az1047-397:67196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0312a9eb2c]
[fv-az1047-397:67196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0312a4527e]
[fv-az1047-397:67196] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0312a288ff]
[fv-az1047-397:67196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0312ea5ff5]
[fv-az1047-397:67196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0312ebb0da]
[fv-az1047-397:67196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0312ea5a55]
[fv-az1047-397:67196] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0312ea5a6f]
[fv-az1047-397:67196] [ 8] plumed(+0x146dd)[0x55e15b59d6dd]
[fv-az1047-397:67196] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0312a2a1ca]
[fv-az1047-397:67196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0312a2a28b]
[fv-az1047-397:67196] [11] plumed(+0x15365)[0x55e15b59e365]
[fv-az1047-397:67196] *** End of error message ***
</pre>
{% endraw %}
