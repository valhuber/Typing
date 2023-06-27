# Experiment with Typing

This is to explore SQLAlchemy 2 typing.

In database/models.py, find: ***# typing***.

Test in declare_logic.py, in `congratulate_sales_rep`.

Status:

1. Seems like optional for strings, int
2. But required for decimal, date - odd
3. Seems to work for Customer.OrdersList
4. But not for anOrder.Customer. (no code completion)

## References

* [typing](https://docs.sqlalchemy.org/en/20/changelog/whatsnew_20.html#sql-expression-statement-result-set-typing)
* [working with related objects](https://docs.sqlalchemy.org/en/20/tutorial/orm_related_objects.html#tutorial-orm-related-objects)

    * [backpopulates not backref](https://docs.sqlalchemy.org/en/14/orm/backref.html)