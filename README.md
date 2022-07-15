# Commit Message Breakdown

This document serves as a reference for generating  standardized and useful commit messages.

## Commit Message Format

    Type(Scope): Subject

    Body (optional)

    Footer (optional)

## Example Commit Messages

#### Example 1

    feat: Created new function for date / time conversion
    
    Issue -> #987

#### Example 2

    fix: Fixed 'null' return bug in 'lower_down' method
    
    Type issue found in 'lower_down'. Added type.
    
    Issue -> #275
    
#### Example 3

    refactor: Cleaned up duplicate variable declarations  
    
    Issue -> #98


## Type

The ___type___ is a field that describes in one word what the commit will be addressing.

### Common types

#### feat
    
- A new feature

#### fix
    
- A bug fix

#### docs
    
- Changes in documentation

#### style
    
- Style changes, formatting, missing semicolons or whitespace

#### refactor
    
- Code changes that neither fixes a bug or adds a feature

#### perf
    
- Changes that improve performance

#### test
    
- Add missing tests

#### chore

- Changes to the build process

## Scope (optional)

The ___scope___ is an _optional_ phrase describing parts of the code affected by the changes.
    
## Subject

The ___subject___ contains a short description of the applied changes.
    
## Body (optional)

The ___body___ is an _optional_ space that is used to provide additional information or context.
    
## Footer (optional)

The ___footer___ is an _optional_ space that can be used to reference an open issue, or other item.
