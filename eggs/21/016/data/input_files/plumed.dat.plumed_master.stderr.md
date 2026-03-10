**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT
[runnervm0kj6c:08157] *** Process received signal ***
[runnervm0kj6c:08157] Signal: Aborted (6)
[runnervm0kj6c:08157] Signal code:  (-6)
[runnervm0kj6c:08157] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb52f045330]
[runnervm0kj6c:08157] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb52f09eb2c]
[runnervm0kj6c:08157] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb52f04527e]
[runnervm0kj6c:08157] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb52f0288ff]
[runnervm0kj6c:08157] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb52f4a5ff5]
[runnervm0kj6c:08157] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb52f4bb0da]
[runnervm0kj6c:08157] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb52f4a5a55]
[runnervm0kj6c:08157] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb52f4a5a6f]
[runnervm0kj6c:08157] [ 8] plumed_master(+0x146dd)[0x55f043ca16dd]
[runnervm0kj6c:08157] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb52f02a1ca]
[runnervm0kj6c:08157] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb52f02a28b]
[runnervm0kj6c:08157] [11] plumed_master(+0x15365)[0x55f043ca2365]
[runnervm0kj6c:08157] *** End of error message ***
</pre>
{% endraw %}
