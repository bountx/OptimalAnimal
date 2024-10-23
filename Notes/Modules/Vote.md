Requires all 10 score categories to not be NULL.

Updates voted [[Individual animal score|animal score]] and add new record in [[Votes]] table.

Each user can only vote one animal once (if already voted it deletes last vote and creates a new one - this way we make sure created at and uuid changes).