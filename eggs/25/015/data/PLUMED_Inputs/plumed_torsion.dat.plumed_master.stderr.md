**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[runnervm0kj6c:04226] *** Process received signal ***
[runnervm0kj6c:04226] Signal: Aborted (6)
[runnervm0kj6c:04226] Signal code:  (-6)
[runnervm0kj6c:04226] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4acb245330]
[runnervm0kj6c:04226] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4acb29eb2c]
[runnervm0kj6c:04226] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4acb24527e]
[runnervm0kj6c:04226] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4acb2288ff]
[runnervm0kj6c:04226] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4acb6a5ff5]
[runnervm0kj6c:04226] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4acb6bb0da]
[runnervm0kj6c:04226] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4acb6a5a55]
[runnervm0kj6c:04226] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4acb6a5a6f]
[runnervm0kj6c:04226] [ 8] plumed_master(+0x146dd)[0x560771ce56dd]
[runnervm0kj6c:04226] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4acb22a1ca]
[runnervm0kj6c:04226] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4acb22a28b]
[runnervm0kj6c:04226] [11] plumed_master(+0x15365)[0x560771ce6365]
[runnervm0kj6c:04226] *** End of error message ***
</pre>
{% endraw %}
