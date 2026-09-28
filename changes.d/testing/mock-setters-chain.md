 -  Fixed the setters that `createFederation()` returns from
    `setActorDispatcher()`, `setObjectDispatcher()`, and the collection
    dispatchers so that every method returns the setters object; chaining them
    now works as it does with the real `Federation`.  The actor setters also
    gained `mapActorAlias()`.  [[#1098]]
