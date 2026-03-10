**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[runnervm0kj6c:10224] *** Process received signal ***
[runnervm0kj6c:10224] Signal: Aborted (6)
[runnervm0kj6c:10224] Signal code:  (-6)
[runnervm0kj6c:10224] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc735245330]
[runnervm0kj6c:10224] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc73529eb2c]
[runnervm0kj6c:10224] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc73524527e]
[runnervm0kj6c:10224] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7352288ff]
[runnervm0kj6c:10224] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc7356a5ff5]
[runnervm0kj6c:10224] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc7356bb0da]
[runnervm0kj6c:10224] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc7356a5a55]
[runnervm0kj6c:10224] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc7356a5a6f]
[runnervm0kj6c:10224] [ 8] plumed_master(+0x146dd)[0x5567fef5e6dd]
[runnervm0kj6c:10224] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc73522a1ca]
[runnervm0kj6c:10224] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc73522a28b]
[runnervm0kj6c:10224] [11] plumed_master(+0x15365)[0x5567fef5f365]
[runnervm0kj6c:10224] *** End of error message ***
</pre>
{% endraw %}
