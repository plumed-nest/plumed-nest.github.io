**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1efa.dat   
Download: [zipped raw stdout](plumed_print_1efa.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print_1efa.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_noTet_99sbws_proc_mod_resID.pdb
[runnervm0kj6c:06966] *** Process received signal ***
[runnervm0kj6c:06966] Signal: Aborted (6)
[runnervm0kj6c:06966] Signal code:  (-6)
[runnervm0kj6c:06966] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb1ece45330]
[runnervm0kj6c:06966] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb1ece9eb2c]
[runnervm0kj6c:06966] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb1ece4527e]
[runnervm0kj6c:06966] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb1ece288ff]
[runnervm0kj6c:06966] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb1ed2a5ff5]
[runnervm0kj6c:06966] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb1ed2bb0da]
[runnervm0kj6c:06966] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb1ed2a5a55]
[runnervm0kj6c:06966] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb1ed2a5a6f]
[runnervm0kj6c:06966] [ 8] plumed_master(+0x146dd)[0x55f6fc1866dd]
[runnervm0kj6c:06966] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb1ece2a1ca]
[runnervm0kj6c:06966] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb1ece2a28b]
[runnervm0kj6c:06966] [11] plumed_master(+0x15365)[0x55f6fc187365]
[runnervm0kj6c:06966] *** End of error message ***
</pre>
{% endraw %}
