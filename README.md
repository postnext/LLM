conditions  []ifCondition
}
// ifCondition can match a WebDAV resource, based on a stateToken or ETag.
// Exactly one of stateToken and entityTag should be non-empty.
type ifCondition struct {
	not        bool
	stateToken string
	entityTag  string# LLM
