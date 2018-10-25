1.批量导入
load DATA LOCAL INFILE '/Users/fengwen/mspace/code/store.csv' IGNORE INTO TABLE
        `store`
        character set utf8
        FIELDS TERMINATED BY ','
        (`store_no`)
         SET pertner_id='9D0BFF4C88C111E885BF0017FA0074B3';
