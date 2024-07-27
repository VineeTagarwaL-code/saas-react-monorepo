# Turbo Set up
Turbo Repo is set up 
## Prisma Import
```js
    import { PrismaClient } from '@repo/db';
    
    const client = new PrismaClient();
```

## Scripts

You now have a reusable @repo/db package that you can import into any of your applications and a turbo db:push script to push schema changes

