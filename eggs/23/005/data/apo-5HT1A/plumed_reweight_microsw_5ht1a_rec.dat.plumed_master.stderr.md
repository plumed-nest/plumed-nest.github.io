**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @73 : keyword ARG is compulsory for this action
[runnervm0kj6c:08552] *** Process received signal ***
[runnervm0kj6c:08552] Signal: Aborted (6)
[runnervm0kj6c:08552] Signal code:  (-6)
[runnervm0kj6c:08552] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad88245330]
[runnervm0kj6c:08552] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad8829eb2c]
[runnervm0kj6c:08552] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad8824527e]
[runnervm0kj6c:08552] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad882288ff]
[runnervm0kj6c:08552] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad886a5ff5]
[runnervm0kj6c:08552] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad886bb0da]
[runnervm0kj6c:08552] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad886a5a55]
[runnervm0kj6c:08552] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad886a5a6f]
[runnervm0kj6c:08552] [ 8] plumed_master(+0x146dd)[0x560fa4d806dd]
[runnervm0kj6c:08552] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad8822a1ca]
[runnervm0kj6c:08552] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad8822a28b]
[runnervm0kj6c:08552] [11] plumed_master(+0x15365)[0x560fa4d81365]
[runnervm0kj6c:08552] *** End of error message ***
</pre>
{% endraw %}
