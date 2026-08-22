**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervm76f27:05327] *** Process received signal ***
[runnervm76f27:05327] Signal: Aborted (6)
[runnervm76f27:05327] Signal code:  (-6)
[runnervm76f27:05327] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3310845330]
[runnervm76f27:05327] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f331089ec0c]
[runnervm76f27:05327] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f331084527e]
[runnervm76f27:05327] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f33108288ff]
[runnervm76f27:05327] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3310ca5ff5]
[runnervm76f27:05327] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3310cbb0da]
[runnervm76f27:05327] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3310ca5a55]
[runnervm76f27:05327] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3310ca5a6f]
[runnervm76f27:05327] [ 8] plumed(+0x146dd)[0x5596d62856dd]
[runnervm76f27:05327] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f331082a1ca]
[runnervm76f27:05327] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f331082a28b]
[runnervm76f27:05327] [11] plumed(+0x15365)[0x5596d6286365]
[runnervm76f27:05327] *** End of error message ***
</pre>
{% endraw %}
