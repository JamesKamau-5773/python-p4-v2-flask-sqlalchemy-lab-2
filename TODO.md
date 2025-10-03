# TODO List for Flask-SQLAlchemy Lab

- [x] Run pipenv install and pipenv shell in root directory
- [ ] Change to server directory and run flask db init, migrate, upgrade
- [ ] Edit server/models.py to add Review model with attributes and relationships
- [x] Run flask db migrate -m 'add review' and upgrade in server directory
- [x] Run pytest testing/review_test.py
- [x] Run python seed.py in server directory
- [x] Add association proxy to Customer model in models.py
- [x] Run pytest testing/association_proxy_test.py
- [x] Add SerializerMixin inheritance and serialize_rules to Customer, Item, Review
- [x] Run pytest testing/serialization_test.py
- [x] Run pytest to run all tests
- [ ] Commit and push changes
