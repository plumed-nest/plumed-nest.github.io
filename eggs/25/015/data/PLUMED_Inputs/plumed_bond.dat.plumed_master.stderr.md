**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervmkj6or:04111] *** Process received signal ***
[runnervmkj6or:04111] Signal: Aborted (6)
[runnervmkj6or:04111] Signal code:  (-6)
[runnervmkj6or:04111] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3c36845330]
[runnervmkj6or:04111] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3c3689eb2c]
[runnervmkj6or:04111] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3c3684527e]
[runnervmkj6or:04111] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3c368288ff]
[runnervmkj6or:04111] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3c36ca5ff5]
[runnervmkj6or:04111] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3c36cbb0da]
[runnervmkj6or:04111] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3c36ca5a55]
[runnervmkj6or:04111] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3c36ca5a6f]
[runnervmkj6or:04111] [ 8] plumed_master(+0x146dd)[0x55789e1126dd]
[runnervmkj6or:04111] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3c3682a1ca]
[runnervmkj6or:04111] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3c3682a28b]
[runnervmkj6or:04111] [11] plumed_master(+0x15365)[0x55789e113365]
[runnervmkj6or:04111] *** End of error message ***
</pre>
{% endraw %}
