**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmvrwv9:06068] *** Process received signal ***
[runnervmvrwv9:06068] Signal: Aborted (6)
[runnervmvrwv9:06068] Signal code:  (-6)
[runnervmvrwv9:06068] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3dd3845330]
[runnervmvrwv9:06068] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3dd389eb2c]
[runnervmvrwv9:06068] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3dd384527e]
[runnervmvrwv9:06068] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3dd38288ff]
[runnervmvrwv9:06068] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3dd3ca5ff5]
[runnervmvrwv9:06068] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3dd3cbb0da]
[runnervmvrwv9:06068] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3dd3ca5a55]
[runnervmvrwv9:06068] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3dd3ca5a6f]
[runnervmvrwv9:06068] [ 8] plumed(+0x146dd)[0x561e6576c6dd]
[runnervmvrwv9:06068] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3dd382a1ca]
[runnervmvrwv9:06068] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3dd382a28b]
[runnervmvrwv9:06068] [11] plumed(+0x15365)[0x561e6576d365]
[runnervmvrwv9:06068] *** End of error message ***
</pre>
{% endraw %}
