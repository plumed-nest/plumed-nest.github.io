**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[runnervm0kj6c:08141] *** Process received signal ***
[runnervm0kj6c:08141] Signal: Aborted (6)
[runnervm0kj6c:08141] Signal code:  (-6)
[runnervm0kj6c:08141] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe95a45330]
[runnervm0kj6c:08141] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe95a9eb2c]
[runnervm0kj6c:08141] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe95a4527e]
[runnervm0kj6c:08141] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe95a288ff]
[runnervm0kj6c:08141] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe95ea5ff5]
[runnervm0kj6c:08141] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe95ebb0da]
[runnervm0kj6c:08141] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe95ea5a55]
[runnervm0kj6c:08141] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe95ea5a6f]
[runnervm0kj6c:08141] [ 8] plumed(+0x146dd)[0x5639fb04d6dd]
[runnervm0kj6c:08141] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe95a2a1ca]
[runnervm0kj6c:08141] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe95a2a28b]
[runnervm0kj6c:08141] [11] plumed(+0x15365)[0x5639fb04e365]
[runnervm0kj6c:08141] *** End of error message ***
</pre>
{% endraw %}
