**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep2/steered_C_P_2.dat   
Download: [zipped raw stdout](steered_C_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_C_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervm0kj6c:04292] *** Process received signal ***
[runnervm0kj6c:04292] Signal: Aborted (6)
[runnervm0kj6c:04292] Signal code:  (-6)
[runnervm0kj6c:04292] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efff4045330]
[runnervm0kj6c:04292] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efff409eb2c]
[runnervm0kj6c:04292] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efff404527e]
[runnervm0kj6c:04292] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efff40288ff]
[runnervm0kj6c:04292] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efff44a5ff5]
[runnervm0kj6c:04292] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efff44bb0da]
[runnervm0kj6c:04292] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efff44a5a55]
[runnervm0kj6c:04292] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efff44a5a6f]
[runnervm0kj6c:04292] [ 8] plumed_master(+0x146dd)[0x55e01f6676dd]
[runnervm0kj6c:04292] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efff402a1ca]
[runnervm0kj6c:04292] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efff402a28b]
[runnervm0kj6c:04292] [11] plumed_master(+0x15365)[0x55e01f668365]
[runnervm0kj6c:04292] *** End of error message ***
</pre>
{% endraw %}
