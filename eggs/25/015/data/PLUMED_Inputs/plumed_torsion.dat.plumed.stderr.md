**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[runnervm0kj6c:04210] *** Process received signal ***
[runnervm0kj6c:04210] Signal: Aborted (6)
[runnervm0kj6c:04210] Signal code:  (-6)
[runnervm0kj6c:04210] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6131845330]
[runnervm0kj6c:04210] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f613189eb2c]
[runnervm0kj6c:04210] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f613184527e]
[runnervm0kj6c:04210] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f61318288ff]
[runnervm0kj6c:04210] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6131ca5ff5]
[runnervm0kj6c:04210] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6131cbb0da]
[runnervm0kj6c:04210] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6131ca5a55]
[runnervm0kj6c:04210] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6131ca5a6f]
[runnervm0kj6c:04210] [ 8] plumed(+0x146dd)[0x55a43a6c16dd]
[runnervm0kj6c:04210] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f613182a1ca]
[runnervm0kj6c:04210] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f613182a28b]
[runnervm0kj6c:04210] [11] plumed(+0x15365)[0x55a43a6c2365]
[runnervm0kj6c:04210] *** End of error message ***
</pre>
{% endraw %}
