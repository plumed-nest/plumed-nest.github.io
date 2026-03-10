**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[runnervm0kj6c:08978] *** Process received signal ***
[runnervm0kj6c:08978] Signal: Aborted (6)
[runnervm0kj6c:08978] Signal code:  (-6)
[runnervm0kj6c:08978] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f014f645330]
[runnervm0kj6c:08978] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f014f69eb2c]
[runnervm0kj6c:08978] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f014f64527e]
[runnervm0kj6c:08978] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f014f6288ff]
[runnervm0kj6c:08978] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f014faa5ff5]
[runnervm0kj6c:08978] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f014fabb0da]
[runnervm0kj6c:08978] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f014faa5a55]
[runnervm0kj6c:08978] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f014faa5a6f]
[runnervm0kj6c:08978] [ 8] plumed_master(+0x146dd)[0x55f50c1786dd]
[runnervm0kj6c:08978] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f014f62a1ca]
[runnervm0kj6c:08978] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f014f62a28b]
[runnervm0kj6c:08978] [11] plumed_master(+0x15365)[0x55f50c179365]
[runnervm0kj6c:08978] *** End of error message ***
</pre>
{% endraw %}
