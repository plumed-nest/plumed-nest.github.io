**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @77 : keyword ARG is compulsory for this action
[runnervm0kj6c:06427] *** Process received signal ***
[runnervm0kj6c:06427] Signal: Aborted (6)
[runnervm0kj6c:06427] Signal code:  (-6)
[runnervm0kj6c:06427] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1b27845330]
[runnervm0kj6c:06427] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1b2789eb2c]
[runnervm0kj6c:06427] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1b2784527e]
[runnervm0kj6c:06427] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1b278288ff]
[runnervm0kj6c:06427] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1b27ca5ff5]
[runnervm0kj6c:06427] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1b27cbb0da]
[runnervm0kj6c:06427] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1b27ca5a55]
[runnervm0kj6c:06427] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1b27ca5a6f]
[runnervm0kj6c:06427] [ 8] plumed_master(+0x146dd)[0x5623c518f6dd]
[runnervm0kj6c:06427] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1b2782a1ca]
[runnervm0kj6c:06427] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1b2782a28b]
[runnervm0kj6c:06427] [11] plumed_master(+0x15365)[0x5623c5190365]
[runnervm0kj6c:06427] *** End of error message ***
</pre>
{% endraw %}
