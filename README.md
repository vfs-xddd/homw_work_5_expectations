# homw_work_5_expectations
Kachaev_MA

batch.expect_column_values_to_be_of_type(column='billing_period', type_='TEXT') - проверяем нужный тип в поле 
batch.expect_column_values_to_not_be_null(column='user_id') - проверяем что ID есть
batch.expect_column_values_to_be_of_type(column='user_id', type_='INTEGER') - и он целочисленный
batch.expect_column_values_to_not_be_null(column='sum') - прочеряем что значение суммы есть
batch.expect_column_values_to_be_of_type(column='phone', type_='TEXT') - проверяем что поле телефон текстовое
batch.expect_column_value_lengths_to_equal(column='phone', value=12) - проверяем что номер телефона из 12 символов
batch.expect_column_values_to_match_regex(column='phone', regex='(\s*)?(\+)?([- _():=+]?\d[- _():=+]?){10,14}(\s*)?') - номер телефона соответствует регулярке


