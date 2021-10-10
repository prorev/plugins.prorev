---
id: 12971
title: data_warehouse_client-1.3.8
date: 2020-02-14
author: auto-mik
layout: post
permalink: /python/data_warehouse_client-1.3.8/
published: true
image:
categories:
   - python
tags:  
   - data_warehouse_client-1.3.8
---
_**Package details:**_



**Name**: data-warehouse-client

**Version**: 1.3.8

**Summary**: This package provides access to the e-Science Central data warehouse that can be used to store, access and analyse data collected in scientific studies, including for healthcare applications

**Home-page**: https://github.com/e-science-central/data-warehouse-client

**Author**: Paul Watson

**Author-email**: paul.watson@ncl.ac.uk

**License**: UNKNOWN



**Number of Python files**: 16



---





- `data_warehouse_client/clone_study_metadata.py` 

   (1369 characters, 178 words)

    _imported modules:_ `data_warehouse_client` 

    _defined functions:_ `clone_study_metadata` 



- `data_warehouse_client/csv_io.py` 

   (2514 characters, 305 words)

    _imported modules:_ `typing`, `csv` 

    _defined functions:_ `export_measurements_as_csv`, `export_measurement_groups_as_csv` 



- `data_warehouse_client/sample_queries.py` 

   (7973 characters, 815 words)

    _imported modules:_ `data_warehouse_client`, `data_warehouse_client`, `data_warehouse_client`, `data_warehouse_client`, `data_warehouse_client`, `datetime` 





- `data_warehouse_client/file_utils.py` 

   (1398 characters, 167 words)

    _imported modules:_ `string`, `pkg_resources` 

    _defined functions:_ `process_sql_template` 



- `data_warehouse_client/study_summary.py` 

   (8022 characters, 840 words)

    _imported modules:_ `tabulate`, `data_warehouse_client`, `data_warehouse_client`, `datetime` 

    _defined functions:_ `get_instances_per_measurement_group`, `print_all_instances_in_a_study`, `print_study_summary`, `mk_txt_report_file_name`, `mk_csv_report_file_name`, `print_all_instances_in_a_study_to_file`, `print_all_instances_in_a_study_to_csv_files`, `print_all_instances_in_a_study_with_local_participant_id_to_csv_files`, `print_study_summary_to_file` 



- `data_warehouse_client/delete_study_contents.py` 

   (2534 characters, 345 words)

    _defined functions:_ `delete_study_contents`, `delete_study_measurements`, `table_names_to_delete`, `measurement_table_names`, `metadata_table_names`, `delete_study_completely` 



- `data_warehouse_client/plot.py` 

   (6131 characters, 613 words)

    _imported modules:_ `data_warehouse_client`, `matplotlib.backends.backend_pdf`, `print_metadata_table`, `datetime` 

    _defined functions:_ `plot_measurements`, `mk_pdf_report_file_name`, `plot_distributions` 



- `data_warehouse_client/__init__.py` 

   (0 characters, 0 words)





- `data_warehouse_client/table_reader_json.py` 

   (1050 characters, 161 words)

    _imported modules:_ `json` 

    _defined functions:_ `read_json_tables` 



- `data_warehouse_client/load_warehouse_helpers.py` 

   (24217 characters, 3198 words)

    _imported modules:_ `functools` 

    _defined functions:_ `process_message_group`, `type_names`, `check_int`, `check_real`, `check_datetime`, `check_boolean`, `type_check`, `get_and_check_value`, `mk_basic_field`, `mk_optional_basic_field`, `mk_int`, `mk_optional_int`, `mk_bounded_int`, `mk_optional_bounded_int`, `mk_real`, `mk_optional_real`, `mk_bounded_real`, `mk_optional_bounded_real`, `mk_string`, `mk_optional_string`, `mk_datetime`, `mk_optional_datetime`, `mk_boolean`, `mk_optional_boolean`, `mk_category_from_dict`, `mk_category_field`, `mk_optional_category_field`, `mk_nominal`, `mk_ordinal`, `mk_nominal_from_id`, `mk_ordinal_from_id`, `mk_optional_nominal_from_dict`, `mk_optional_nominal_from_id`, `mk_optional_ordinal_from_dict`, `mk_optional_ordinal_from_id`, `split_enum`, `get_converter_fn` 



- `data_warehouse_client/transform_result_format.py` 

   (6162 characters, 726 words)

    _defined functions:_ `form_measurements`, `form_measurement_group` 



- `data_warehouse_client/data_warehouse.py` 

   (36702 characters, 3623 words)

    _imported modules:_ `datetime`, `sys`, `psycopg2`, `json`, `more_itertools`, `data_warehouse_client`, `data_warehouse_client` 

    _defined classes:_ `DataWarehouse` 

    _defined functions:_ `get_participants_in_result`, `field_holding_value`, `mk_where_condition`, `core_sql_from_for_measurements`, `core_sql_for_where_clauses`, `core_sql_for_where_clauses_for_cohort`, `make_value_test`, `core_sql_select_for_measurements`, `core_sql_for_measurements` 



- `data_warehouse_client/table_writer_json.py` 

   (4380 characters, 535 words)

    _imported modules:_ `json`, `os` 

    _defined functions:_ `table_to_dictionary`, `tables_to_dictionary`, `data_warehouse_metadata_tables_to_dictionary`, `metadata_table_names`, `dictionary_to_json_file`, `data_warehouse_metadata_tables_to_file`, `write_tables_in_dw_from_dictionary`, `insert_rows_in_dw_from_dictionary` 



- `data_warehouse_client/warehouse_checker.py` 

   (10208 characters, 1141 words)

    _imported modules:_ `data_warehouse_client`, `data_warehouse_client`, `data_warehouse_client`, `tabulate`, `datetime` 

    _defined functions:_ `check_category_exists`, `check_integer_bounds_exist`, `check_real_bounds_exist`, `check_valtype_matches_values`, `check_category_in_range`, `check_bounded_integers`, `check_bounded_reals`, `print_check_warehouse`, `mk_txt_report_file_name`, `print_check_warehouse_to_file` 



- `data_warehouse_client/print_io.py` 

   (3845 characters, 454 words)

    _imported modules:_ `typing`, `tabulate` 

    _defined functions:_ `print_rows`, `print_measurement_group_instances`, `print_measurements`, `print_rows_to_file`, `print_measurement_group_instances_to_file`, `print_measurements_to_file` 



- `data_warehouse_client/print_metadata_table.py` 

   (7409 characters, 719 words)

    _imported modules:_ `data_warehouse_client`, `tabulate`, `datetime` 

    _defined functions:_ `valuetype_to_name`, `mk_txt_report_file_name`, `print_metadata_tables_to_file`, `print_metadata_tables`, `mk_optional`, `create_measurement_group_info` 