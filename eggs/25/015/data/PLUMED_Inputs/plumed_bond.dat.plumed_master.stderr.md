**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervm76f27:05342] *** Process received signal ***
[runnervm76f27:05342] Signal: Aborted (6)
[runnervm76f27:05342] Signal code:  (-6)
[runnervm76f27:05342] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd96d245330]
[runnervm76f27:05342] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd96d29ec0c]
[runnervm76f27:05342] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd96d24527e]
[runnervm76f27:05342] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd96d2288ff]
[runnervm76f27:05342] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd96d6a5ff5]
[runnervm76f27:05342] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd96d6bb0da]
[runnervm76f27:05342] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd96d6a5a55]
[runnervm76f27:05342] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd96d6a5a6f]
[runnervm76f27:05342] [ 8] plumed_master(+0x146dd)[0x56214b64a6dd]
[runnervm76f27:05342] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd96d22a1ca]
[runnervm76f27:05342] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd96d22a28b]
[runnervm76f27:05342] [11] plumed_master(+0x15365)[0x56214b64b365]
[runnervm76f27:05342] *** End of error message ***
</pre>
{% endraw %}
