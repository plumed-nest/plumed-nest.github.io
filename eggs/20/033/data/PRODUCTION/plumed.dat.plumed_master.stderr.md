**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0, REF1, REF2
[runnervm0kj6c:09934] *** Process received signal ***
[runnervm0kj6c:09934] Signal: Aborted (6)
[runnervm0kj6c:09934] Signal code:  (-6)
[runnervm0kj6c:09934] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f03a3c45330]
[runnervm0kj6c:09934] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f03a3c9eb2c]
[runnervm0kj6c:09934] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f03a3c4527e]
[runnervm0kj6c:09934] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03a3c288ff]
[runnervm0kj6c:09934] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f03a40a5ff5]
[runnervm0kj6c:09934] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f03a40bb0da]
[runnervm0kj6c:09934] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f03a40a5a55]
[runnervm0kj6c:09934] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f03a40a5a6f]
[runnervm0kj6c:09934] [ 8] plumed_master(+0x146dd)[0x5589b45166dd]
[runnervm0kj6c:09934] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f03a3c2a1ca]
[runnervm0kj6c:09934] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f03a3c2a28b]
[runnervm0kj6c:09934] [11] plumed_master(+0x15365)[0x5589b4517365]
[runnervm0kj6c:09934] *** End of error message ***
</pre>
{% endraw %}
