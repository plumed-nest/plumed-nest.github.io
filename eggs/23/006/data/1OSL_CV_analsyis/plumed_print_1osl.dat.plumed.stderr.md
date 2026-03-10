**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[runnervm0kj6c:07004] *** Process received signal ***
[runnervm0kj6c:07004] Signal: Aborted (6)
[runnervm0kj6c:07004] Signal code:  (-6)
[runnervm0kj6c:07004] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f66d9645330]
[runnervm0kj6c:07004] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f66d969eb2c]
[runnervm0kj6c:07004] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f66d964527e]
[runnervm0kj6c:07004] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f66d96288ff]
[runnervm0kj6c:07004] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f66d9aa5ff5]
[runnervm0kj6c:07004] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f66d9abb0da]
[runnervm0kj6c:07004] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f66d9aa5a55]
[runnervm0kj6c:07004] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f66d9aa5a6f]
[runnervm0kj6c:07004] [ 8] plumed(+0x146dd)[0x557de4ed76dd]
[runnervm0kj6c:07004] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f66d962a1ca]
[runnervm0kj6c:07004] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f66d962a28b]
[runnervm0kj6c:07004] [11] plumed(+0x15365)[0x557de4ed8365]
[runnervm0kj6c:07004] *** End of error message ***
</pre>
{% endraw %}
