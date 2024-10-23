**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[fv-az1442-469:05794] *** Process received signal ***
[fv-az1442-469:05794] Signal: Aborted (6)
[fv-az1442-469:05794] Signal code:  (-6)
[fv-az1442-469:05794] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0a88e42520]
[fv-az1442-469:05794] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0a88e969fc]
[fv-az1442-469:05794] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0a88e42476]
[fv-az1442-469:05794] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0a88e287f3]
[fv-az1442-469:05794] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0a892a2b9e]
[fv-az1442-469:05794] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0a892ae20c]
[fv-az1442-469:05794] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0a892ae277]
[fv-az1442-469:05794] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0a892ae52b]
[fv-az1442-469:05794] [ 8] plumed_master(+0x14254)[0x55c2bbcb0254]
[fv-az1442-469:05794] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0a88e29d90]
[fv-az1442-469:05794] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0a88e29e40]
[fv-az1442-469:05794] [11] plumed_master(+0x14eb5)[0x55c2bbcb0eb5]
[fv-az1442-469:05794] *** End of error message ***
</pre>
{% endraw %}
