
##建表语句
CREATE TABLE JPA_TEST (
    PROW_ID VARCHAR(32) PRIMARY KEY COMMENT '无业务含义主键'
  , INSURACE_CODE VARCHAR(4) COMMENT '保险公司代码'
  , ETL_DATE DATE COMMENT 'ETL日期'
  , TIMES INT COMMENT '入库次数'
  , LAST_UPDATE_TS  TIMESTAMP COMMENT 'LAST_UPDATE_TS'
);
