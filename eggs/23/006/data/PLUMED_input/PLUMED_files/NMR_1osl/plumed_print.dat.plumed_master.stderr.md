**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[runnervm0kj6c:07071] *** Process received signal ***
[runnervm0kj6c:07071] Signal: Aborted (6)
[runnervm0kj6c:07071] Signal code:  (-6)
[runnervm0kj6c:07071] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef33245330]
[runnervm0kj6c:07071] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef3329eb2c]
[runnervm0kj6c:07071] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef3324527e]
[runnervm0kj6c:07071] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef332288ff]
[runnervm0kj6c:07071] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef336a5ff5]
[runnervm0kj6c:07071] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef336bb0da]
[runnervm0kj6c:07071] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef336a5a55]
[runnervm0kj6c:07071] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef336a5a6f]
[runnervm0kj6c:07071] [ 8] plumed_master(+0x146dd)[0x555f85f766dd]
[runnervm0kj6c:07071] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef3322a1ca]
[runnervm0kj6c:07071] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef3322a28b]
[runnervm0kj6c:07071] [11] plumed_master(+0x15365)[0x555f85f77365]
[runnervm0kj6c:07071] *** End of error message ***
</pre>
{% endraw %}
