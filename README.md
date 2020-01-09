# M2-HANDBOOK - Notes for Magento2

Magento2 Profiler Impliemntation: <br/>

Source: https://blog.e-zest.com/magento-2-static-code-analysis#top <br/>

github coding standards: https://github.com/magento/magento-coding-standard <br/>


<h2>ENABLE HTML PROFILER IN MAGENTO2</h2>
Add SetEnv MAGE_PROFILER "html" in .htaccess in your project


<h2> Mysql Optmization : add below lines in /etc/mysql/my.cnf</h2>
<pre>
[mysqld]
query_cache_type=1
query_cache_size=512M
query_cache_limit=512M
innodb_buffer_pool_size=4096M
innodb_flush_log_at_trx_commit=0
max_heap_table_size=768M
tmp_table_size=768M
innodb_log_file_size=1024M
</pre>
