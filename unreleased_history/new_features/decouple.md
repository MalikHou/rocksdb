* New option `BlockBasedTableOptions::decouple_partitioned_filters` should improve efficiency in serving read queries because filter and index partitions can consistently target the configured `metadata_block_size`. This option is currently opt-in.