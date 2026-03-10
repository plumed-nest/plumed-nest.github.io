**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[runnervm0kj6c:08962] *** Process received signal ***
[runnervm0kj6c:08962] Signal: Aborted (6)
[runnervm0kj6c:08962] Signal code:  (-6)
[runnervm0kj6c:08962] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe146645330]
[runnervm0kj6c:08962] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe14669eb2c]
[runnervm0kj6c:08962] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe14664527e]
[runnervm0kj6c:08962] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe1466288ff]
[runnervm0kj6c:08962] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe146aa5ff5]
[runnervm0kj6c:08962] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe146abb0da]
[runnervm0kj6c:08962] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe146aa5a55]
[runnervm0kj6c:08962] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe146aa5a6f]
[runnervm0kj6c:08962] [ 8] plumed(+0x146dd)[0x55cea56d76dd]
[runnervm0kj6c:08962] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe14662a1ca]
[runnervm0kj6c:08962] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe14662a28b]
[runnervm0kj6c:08962] [11] plumed(+0x15365)[0x55cea56d8365]
[runnervm0kj6c:08962] *** End of error message ***
</pre>
{% endraw %}
