**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[runnervm76f27:07108] *** Process received signal ***
[runnervm76f27:07108] Signal: Aborted (6)
[runnervm76f27:07108] Signal code:  (-6)
[runnervm76f27:07108] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1283445330]
[runnervm76f27:07108] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f128349ec0c]
[runnervm76f27:07108] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f128344527e]
[runnervm76f27:07108] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f12834288ff]
[runnervm76f27:07108] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12838a5ff5]
[runnervm76f27:07108] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12838bb0da]
[runnervm76f27:07108] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12838a5a55]
[runnervm76f27:07108] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12838a5a6f]
[runnervm76f27:07108] [ 8] plumed(+0x146dd)[0x55ab2d1536dd]
[runnervm76f27:07108] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f128342a1ca]
[runnervm76f27:07108] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f128342a28b]
[runnervm76f27:07108] [11] plumed(+0x15365)[0x55ab2d154365]
[runnervm76f27:07108] *** End of error message ***
</pre>
{% endraw %}
