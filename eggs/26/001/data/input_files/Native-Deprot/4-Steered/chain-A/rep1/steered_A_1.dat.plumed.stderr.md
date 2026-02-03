**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Native-Deprot/4-Steered/chain-A/rep1/steered_A_1.dat   
Download: [zipped raw stdout](steered_A_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_A_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/ermsd_ref.pdb
[runnervmkj6or:05115] *** Process received signal ***
[runnervmkj6or:05115] Signal: Aborted (6)
[runnervmkj6or:05115] Signal code:  (-6)
[runnervmkj6or:05115] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7861845330]
[runnervmkj6or:05115] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f786189eb2c]
[runnervmkj6or:05115] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f786184527e]
[runnervmkj6or:05115] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f78618288ff]
[runnervmkj6or:05115] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7861ca5ff5]
[runnervmkj6or:05115] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7861cbb0da]
[runnervmkj6or:05115] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7861ca5a55]
[runnervmkj6or:05115] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7861ca5a6f]
[runnervmkj6or:05115] [ 8] plumed(+0x146dd)[0x5599085d26dd]
[runnervmkj6or:05115] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f786182a1ca]
[runnervmkj6or:05115] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f786182a28b]
[runnervmkj6or:05115] [11] plumed(+0x15365)[0x5599085d3365]
[runnervmkj6or:05115] *** End of error message ***
</pre>
{% endraw %}
