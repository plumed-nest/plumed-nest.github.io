**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[fv-az1442-469:05763] *** Process received signal ***
[fv-az1442-469:05763] Signal: Aborted (6)
[fv-az1442-469:05763] Signal code:  (-6)
[fv-az1442-469:05763] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa9ce842520]
[fv-az1442-469:05763] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa9ce8969fc]
[fv-az1442-469:05763] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa9ce842476]
[fv-az1442-469:05763] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa9ce8287f3]
[fv-az1442-469:05763] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa9ceca2b9e]
[fv-az1442-469:05763] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa9cecae20c]
[fv-az1442-469:05763] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa9cecae277]
[fv-az1442-469:05763] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa9cecae52b]
[fv-az1442-469:05763] [ 8] plumed_master(+0x14254)[0x56314bcac254]
[fv-az1442-469:05763] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa9ce829d90]
[fv-az1442-469:05763] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa9ce829e40]
[fv-az1442-469:05763] [11] plumed_master(+0x14eb5)[0x56314bcaceb5]
[fv-az1442-469:05763] *** End of error message ***
</pre>
{% endraw %}
