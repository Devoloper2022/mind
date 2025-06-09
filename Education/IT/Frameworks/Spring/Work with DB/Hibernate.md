Object of class [com.softpower.models.Material] with identifier [2]: optimistic locking failed; nested exception is org.hibernate.StaleObjectStateException: Row was updated or deleted by another transaction (or unsaved-value mapping was incorrect) : [com.softpower.models.Material#2]



 Not allowed to create transaction on shared EntityManager - use Spring transactions or EJB CMT instead; nested exception is java.lang.IllegalStateException: Not allowed to create transaction on shared EntityManager - use Spring transactions or EJB CMT instead


Batch update returned unexpected row count from update [0]; actual row count: 0; expected: 1; statement executed: delete from material where id=?